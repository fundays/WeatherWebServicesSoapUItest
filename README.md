# WeatherWebServicesSoapUItest

## EndPoint

http://ws.webxml.com.cn/WebServices/WeatherWS.asmx 


## WSDL

http://ws.webxml.com.cn/WebServices/WeatherWS.asmx?WSDL


## API

getRegionCountry		http://WebXml.com.cn/getRegionCountry

getRegionDataset		http://WebXml.com.cn/getRegionDataset

getRegionProvince		http://WebXml.com.cn/getRegionProvince

getSupportCityDataset		http://WebXml.com.cn/getSupportCityDataset

getSupportCityString	  http://WebXml.com.cn/getSupportCityString

getWeather		http://WebXml.com.cn/getWeather


## Function Test 
WeatherWSSoap TestSuite 

  - getRegionCountry TestCase

  - getRegionDataset TestCase
  
  - getRegionProvince TestCase
  
  - getSupportCityDataset TestCase
  
  - getSupportCityString TestCase
  
  - getWeather TestCase
  
Test Structure
  
  - Test Steps 
  
    - Assertions 
  
  - Load Tests
  
    - Assertions 
  
  - Security Tests
  
    - Assertions 
    
    
## E2E Integration TestSuite

GetFlowOne

- > Test Steps (4)
  
  - step1: getRegionCountry
  
  - step2: getRegionDataset
  
  - step3: getWeather
  
  - Properties
  
  - LoadTest 1
  
GetFlowTwo

- > Test Steps (3)

  - step1: getSupportProvience
  
  - step2: Property Transfer
  
  - step3: getSupportCityString

  - Load Tests
