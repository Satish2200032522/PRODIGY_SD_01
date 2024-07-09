# PRODIGY_SD_01

Create a program that convertstemperatures between Celsius,Fahrenheit, and Kelvin scales. Theprogram should prompt the user toinput a temperature value and theoriginal unit of measurement. Itshould then convert the temperatureto the other two units and displaythe converted values to the user. Forexample, if the user enters atemperature of 25 degrees Celsius,the program should convert it toFahrenheit and Kelvin, and presentthe converted values as outputs.

explanation: Functions to Convert Temperatures
celsiusToFahrenheit(c): Converts Celsius to Fahrenheit.
celsiusToKelvin(c): Converts Celsius to Kelvin.
fahrenheitToCelsius(f): Converts Fahrenheit to Celsius.
fahrenheitToKelvin(f): Converts Fahrenheit to Kelvin.
kelvinToCelsius(k): Converts Kelvin to Celsius.
kelvinToFahrenheit(k): Converts Kelvin to Fahrenheit.
Main Program
Console Message: Displays a welcome message for the temperature converter.
Loop for User Interaction:
Continuously prompts the user for input until they decide to stop.
Get Temperature and Unit: Uses prompt to get the temperature value and the unit of measurement from the user.
Convert Temperature: Checks the unit and converts the temperature accordingly, then displays the results using console.log.
Continue or Exit: Asks the user if they want to convert another temperature. If the user inputs anything other than "y", the loop breaks, ending the program.
