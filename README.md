# Kelvin To Fahrenheit Project
Kelvin to Fahrenheit project is a mini JavaScript application in the console that converts the temperature from Kelvin to Fahrenheit. 

## Table of contents
* [Instructions](#instructions)
* [Technologies](#technologies)

## Instructions
Challenge: Convert any given temperature in Kelvin to Fahrenheit

1. Let's imagine that the weather reports says that the temperature today will be  301 Kelvin. How should you dress for the day? Let's create an app that lets us know the temperature in fahrenheit. To start, create a variable named kelvinTemp, and set it equal to 301. Write a comment above that explains this line of code.

2. Finding the temperature in Celsius is similar to Kelvin — the only difference is that Celsius is 273.15 degrees less than Kelvin.

Let's convert Kelvin to Celsius by subtracting 273.15 from the kelvinTemp variable. Store the result in another variable, named celsiusTemp.

Write a comment above that explains this line of code.

3. Use this equation to calculate Fahrenheit, then store the answer in a variable named fahrenheitTemp.

Fahrenheit = Celsius * (9/5) + 32

In the next step we will round the number saved to fahrenheitTemp. Write a comment above that explains this line of code.

4. Log to the console the value of  fahrenheitTemp. In our next step we are going to see what we can do to make sure that our number is a whole number by rounding down. The value you logged to the console should begin with 82.13

5. As we have just seen, when you convert from Celsius to Fahrenheit, you often get a decimal number. Go ahead and delete the console log code from step 4.

Use the .floor() method from the Math library to round down the Fahrenheit temperature. Save the result to the fahrenheitTemp variable. Check out the documentation for Math.floor() here: http://bit.ly/javascript-math-floor. Because this is a new concept we haven't covered yet, you may want to watch the next video if you get stuck at this point. This will round your decimal down no matter what the value. Other methods from the Math library you might try out are .round() and ceil(). Write a comment above that explains this line of code.

6. Use console.log and string concatenation to log the temperature in fahrenheitTemp to the console to create the message as follows: The temperature is TEMPERATURE degrees Fahrenheit. TEMPERATURE should be determined by the value of fahrenheitTemp.

## Technologies
Project is created with:
* HTML
* Javascript