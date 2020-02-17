# Overview

Module Name: Leya Analytics Adapter
Module Type: Analyics Adapter
Maintainer: daniel@leya.dev

# Test Parameters
```
   {
     provider: 'leya',
       options : {
         version: "v1.0.0", //optional, if absent defaults to prebid version   
         tags: ["key","value"], //optional, requires an even sized array
         token: 'YOUR_INGESTION_KEY' //required  
       }
   }
```