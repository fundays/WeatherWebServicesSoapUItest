# WeatherWebServicesSoapUItest

The soapUI test project include test steps for function test, End2End integration test, Assertions, load tests with threads set as 5 - 10 and mock test suites for security test. This can be further extended to test on JDBC request and integrate with Groovy scripts to load web's cookies and etc. The load test here can be converted into LoadUI tests. Will make further improvement when have time. 

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
  
  - Property Transfer
  
  - step2: getSupportCityString

  - Load Tests

Further Extension:

## Build test suites - Assertions 

-- xpath Match 

-- xQuery Match 

-- Script Assertion 

-- JMS (Status , timeout )

-- Security (Sensitive Information Exposure )

-- SLA 

-- Compliance, Status, and Standards

## Settings

SSL Setting 

UI Setting 

WS-A Setting 

Web Recording Setting 

## Load test 
Strategy
  
  Burst 
  
  Simple 
  
  Thread 
  
  Variance 

## Security Scan 

Boundary Scan

Cross Site Scripting

Custom Script 

Fuzzing Scan

Invalid Types

Malformed XML

Malicious Attachment

SQL Injection 

