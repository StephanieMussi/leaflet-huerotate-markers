# Leaflet Hue Rotate Markers
## Change colors of the Leaflet marker without any additional library

This repository provides the <style> definition that changes the color of Leaflet markers with the following parameter:
  - hue-rotate(deg)
  - brightness(%)
  - saturate(%)

The resultant colors match the colors displayed in the map legend, which uses the names of HTML color names that are supported by all browsers (https://www.w3schools.com/colors/colors_names.asp). 

| HTML color name  | Hue rotate style | Demo |
| ------------- | ------------- | ------------- |
| [Orchid](https://www.w3schools.com/colors/color_tryit.asp?color=Orchid)  | `.leaflet-color-orchid {filter: hue-rotate(80deg) brightness(130%) saturate(60%);}` | ![0orchid-1](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/c202f68d-5d90-46d6-b726-96ca5033a170) |
| [BlueViolet](https://www.w3schools.com/colors/color_tryit.asp?color=BlueViolet) | `.leaflet-color-blueviolet {filter: hue-rotate(55deg) brightness(100%) saturate(100%);}` | ![0blueviolet](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/b9b4253e-4295-4016-a815-67f6c5852ce0) |
| [CornflowerBlue](https://www.w3schools.com/colors/color_tryit.asp?color=CornflowerBlue) | `.leaflet-color-cornflowerblue {filter: hue-rotate(20deg) brightness(135%) saturate(80%);}` | ![0cornflowerblue](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/3244cf3f-9da1-46e3-b073-73ddef727e70)
| [SaddleBrown](https://www.w3schools.com/colors/color_tryit.asp?color=SaddleBrown) | `.leaflet-color-saddlebrown {filter: hue-rotate(180deg) brightness(100%) saturate(45%);}` | ![0saddlebrown](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/ceaba5db-0b61-463d-8098-80d87a29e063) |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |


  
### References:
  
- Leaflet, an open-source JavaScript library for mobile-friendly interactive maps: https://leafletjs.com/
- W3 Schools HTML Color Names: https://www.w3schools.com/colors/colors_names.asp
