# CO2 emission calculator

A webpage site that returns the amount of CO2-equivalent that will be caused when traveling between two cities using a given transportation method.

## Compilation - How to Compile

As it is a web page, it will not be necessary to compile the program: simply,  you must have internet access (due to the use of open APIs) and use it in your preferred web browser.

The application runs on Windows, Linux and MacOS.

## Running the tests

1. Set-up value of the token on field called ORS_TOKEN;
2. Inform the start and end cities on specific fields;
3. Select the Transportation Method, using options avaliable;
4. Click on the "Calculate CO2 Equivalent"

Try to call the program with incorrect information or with cities where it is not possible to travel using motor vehicles only.
### First unit test - Success Case
Parameters:
    Star City= Munchen
    End City= Rome
    Transportation Method= Petrol Car (Large)
Response:
    Distance: 933.97 km
    Your trip caused 263.38kg of CO2-equivalent.



## Executing - How to Execute

Similar to previous step:
1. Set-up value of the token on field called ORS_TOKEN;
2. Inform the start and end cities on specific fields;
3. Select the transportation-method, using options avaliable;
4. Click on the "Calculate CO2 Equivalent"

![Example: how to Execute](https://github.com/wfcancan/co2_calculator/blob/master/example_co2.png)

## Built With
* [OpenRouteService](https://openrouteservice.org/) - APIs to get coordinates and calculate distance between two points
* [OpenLayers](http://openlayers.org) - The web framework used

## Authors

* **Wellington Fazzi Cancian** - [wfcancian](https://github.com/wfcancan)
