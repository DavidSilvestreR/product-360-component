# \<product-360-component\>

this is a viwer porducto of products in 360

## Properties

|   Properties  | value (default) |                                                      description                                                      |
|:-------------:|:---------------:|:---------------------------------------------------------------------------------------------------------------------:|
| arrayImageSrc |        []       | This property receives an array with the path of the product images.                                                  |
|     images    |        []       | This property saves an array of img elements with each of the addresses provided by the arrayImageSrc array           |
|     canvas    |        ""       | this property saves the html canvas element                                                                           |
| contextCanvas |        ""       | Saves the 2d context of the canvas element                                                                            |
|    controls   |      false      | This property by default is false, if it is placed as an attribute in the element it will show the component controls |
|  oldPositionX |        0        | Tproperty saves the X and Y position of the cursor when it passes the canvas                                          |
|   widthImage  |        0        | this property sets the width of the images that will be represented on the canvas                                     |
|  heightImage  |        0        | this property sets the heigh of the images that will be represented on the canvas                                     |
|  canvasHeight |        0        | this property sets the width of the  canvas                                                                           |
|  canvaswidth  |        0        | this property sets the heigh of the canvas                                                                            |

##Styling

| Variable                       | Type  | Used                                                   |
|--------------------------------|-------|--------------------------------------------------------|
| --product-360-component        | Mixin | host styling of the product 360 component              |
| --product-360-canvas           | Mixin | controls the styles of the canvas element              |
| --product-360-buttos-container | Mixin | this mixin controls of container styles of the buttons |
| --product-360-buttos-general   | Mixin | controls the general button styles                     |
| --product-360-button-right     | Mixin | controls the styles specifically for the right button  |
| --product-360-button-left      | Mixin | controls the styles specifically for the left button   |
| --product-360-button-play      | Mixin | controls the styles specifically for the play button   |




## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
