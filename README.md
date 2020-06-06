# Node.js script for convert address to long, lat 

## How to use
    npm install  
    node convert.js OR npm start

## How is work
Replace the const capital with your list of desired convert address list.

My expample is based of list capital by ISO2  
http://country.io/capital.json

ex :   
```javascript
const capital = {"BD": "Dhaka"};   
{KEY, ADDRESS};
```

The script create a file capital.json in root and replace the address by long lat.   
ex :  
```javascript
{"BD":["90.3788136","23.7593572"]}   
{KEY, [LONG, LAT}}
```  
