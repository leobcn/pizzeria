Documentation
===============

## Resources

The endpoints work with type of chart as a name and expect
requests with *GET* http method

`GET /pie...` 

## General parameters

Every endpoint has the *h* and *w* parameters on url to define the 
height and width of the generated image. 
To request a pie chart with width=800px and hegiht=600px use

`GET /pie?w=800&h=600...` 
When a parameter represents many data you should use a comma as separator.

## Endpoints

Read about the chart types:

* [Pie](./pie.md)
* [Bar](./bar.md)
* [Line](./line.md)
