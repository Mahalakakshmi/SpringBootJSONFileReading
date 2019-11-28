# SpringBootJSONFileReading
Reading a JSONObject File and Filtering Objects ,testing using Postman Rest
*** ESURE Junior Developer Coding Challenge ***

** Scenario **
We have a new requirement to produce a service that allows us to filter the cars in our database by colour.

** Task **
Produce a Spring Boot REST API that reads in data from a JSON file and allows the user to filter by colour.

** URL Format **
The URL should look similar to: http://localhost:8080/cars?colour=red

** Input Data **
The input data is in the included JSON file (cars.json).

It is of the form:
{
    "cars": [
        {
            "brand": "ford",
            "model": "fiesta",
            "fuel": "petrol",
            "doors": 5,
            "colour": "blue"
        }
    ]
}

** Output Format **
You are free to choose the way the data is structured in the response but it should be in JSON format
