# Software Engineering homework

Build and Run

        gradle bootRun
        curl http://localhost:8080/?year=2019

Examples

        request: curl http://localhost:8080/?year=2019
        response: {"errorCode":200,"date":"13/09/19"}
  
        request: curl http://localhost:8080/?year=2020
        response: {"errorCode":200,"date":"12/09/20"}
        
        request: curl http://localhost:8080/?year=2021
        response: {"errorCode":200,"date":"13/09/21"}
        
        request: curl http://localhost:8080/?year=2022
        response: {"errorCode":200,"date":"13/09/22"}
        
        request: curl http://localhost:8080/?year=2023
        response: {"errorCode":200,"date":"13/09/23"}
        
        request: curl http://localhost:8080/?year=2024
        response: {"errorCode":200,"date":"12/09/24"}
        
        request: curl http://localhost:8080?year=0  
        response: {"errorCode":400, "date":"Incorrect year!"}
        