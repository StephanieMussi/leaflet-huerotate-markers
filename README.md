# Leaflet Hue Rotate Markers
## Change colors of the Leaflet marker without any additional library

This repository provides the <style> definition that changes the color of Leaflet markers with the following parameter:
  - hue-rotate(deg)
  - brightness(%)
  - saturate(%)

The resultant colors match the colors displayed in the map legend, which use the names of the pre-defined HTML color names that are supported by all browsers (https://www.w3schools.com/colors/colors_names.asp). 

| HTML color name  | Hue rotate style | Demo |
| ------------- | ------------- | ------------- |
| [Orchid](https://www.w3schools.com/colors/color_tryit.asp?color=Orchid)  | `.leaflet-color-orchid {filter: hue-rotate(80deg) brightness(130%) saturate(60%);}` | ![0orchid-1](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/c202f68d-5d90-46d6-b726-96ca5033a170) |
| [BlueViolet](https://www.w3schools.com/colors/color_tryit.asp?color=BlueViolet) | `.leaflet-color-blueviolet {filter: hue-rotate(55deg) brightness(100%) saturate(100%);}` | ![0blueviolet](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/b9b4253e-4295-4016-a815-67f6c5852ce0) |
| [CornflowerBlue](https://www.w3schools.com/colors/color_tryit.asp?color=CornflowerBlue) | `.leaflet-color-cornflowerblue {filter: hue-rotate(20deg) brightness(135%) saturate(80%);}` | ![0cornflowerblue](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/3244cf3f-9da1-46e3-b073-73ddef727e70)
| [SaddleBrown](https://www.w3schools.com/colors/color_tryit.asp?color=SaddleBrown) | `.leaflet-color-saddlebrown {filter: hue-rotate(180deg) brightness(100%) saturate(45%);}` | ![0saddlebrown](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/ceaba5db-0b61-463d-8098-80d87a29e063) |
| [Salmon](https://www.w3schools.com/colors/color_tryit.asp?color=Salmon) | `.leaflet-color-salmon {filter: hue-rotate(150deg) brightness(150%) saturate(90%);}` | ![0salmon](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/1d11cbde-61e5-4ddb-8403-a657db771d5a) |
| [Khaki](https://www.w3schools.com/colors/color_tryit.asp?color=Khaki) | `.leaflet-color-khaki {filter: hue-rotate(210deg) brightness(185%) saturate(35%);}` | ![0khaki](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/1a7d7f0c-3996-4d86-85ed-de5aca8410c1) |
| [IndianRed](https://www.w3schools.com/colors/color_tryit.asp?color=IndianRed) | `.leaflet-color-indianred {filter: hue-rotate(150deg) brightness(110%) saturate(60%);}` | ![0indianred](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/9fb01f02-26fa-41ba-9bda-b577a2836d2b) |
| [DarkOrange](https://www.w3schools.com/colors/color_tryit.asp?color=DarkOrange) | `.leaflet-color-darkorange {filter: hue-rotate(200deg) brightness(135%) saturate(400%);}` | ![0darkorange](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/637d1cd3-6e74-4efb-adf0-76469183ff72) |
| [Green](https://www.w3schools.com/colors/color_tryit.asp?color=Green) | `.leaflet-color-green {filter: hue-rotate(270deg) brightness(100%) saturate(100%);}` | ![0green](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/a7b2c47f-782d-4a68-b470-ed3f1372dc42) |
| [DimGrey](https://www.w3schools.com/colors/color_tryit.asp?color=DimGrey) | `.leaflet-color-dimgrey {filter: hue-rotate(0deg) brightness(110%) saturate(0%);}` | ![0dimgrey](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/dabf6707-872a-4990-abf5-1bf4e334f44b) |
| [DeepPink](https://www.w3schools.com/colors/color_tryit.asp?color=DeepPink) | `.leaflet-color-deeppink {filter: hue-rotate(115deg) brightness(100%) saturate(130%);}` | ![0deeppink](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/41d2f343-80c3-4b2c-b830-d201e9ac5867) |
| [Magenta](https://www.w3schools.com/colors/color_tryit.asp?color=Magenta) | `.leaflet-color-magenta {filter: hue-rotate(80deg) brightness(110%) saturate(180%);}` | ![0magenta](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/9d0d943f-2a9d-4dac-8553-64f57431a103) |
| [Red](https://www.w3schools.com/colors/color_tryit.asp?color=Red) | `.leaflet-color-red {filter: hue-rotate(150deg) brightness(100%) saturate(250%);}` | ![0red](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/3417c8ef-8ba6-4851-9f9f-72e12128a566)|
| [Cyan](https://www.w3schools.com/colors/color_tryit.asp?color=Cyan) | `.leaflet-color-cyan {filter: hue-rotate(330deg) brightness(170%) saturate(180%);}` | ![0cyan](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/5e33f755-5757-4a65-901a-bf5e193d7cc5) |
| [Yellow](https://www.w3schools.com/colors/color_tryit.asp?color=Yellow) | `.leaflet-color-yellow {filter: hue-rotate(215deg) brightness(200%) saturate(180%);}` | ![0yellow](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/715899c4-0a38-4bc7-adee-4b9f018a839e) |
| [Lime](https://www.w3schools.com/colors/color_tryit.asp?color=Lime) | `.leaflet-color-lime {filter: hue-rotate(280deg) brightness(150%) saturate(150%);}` | ![0lime](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/2e598b82-18fe-4864-b7ef-41055ccc7edf) |
| [OrangeRed](https://www.w3schools.com/colors/color_tryit.asp?color=OrangeRed) | `.leaflet-color-orangered {filter: hue-rotate(170deg) brightness(110%) saturate(130%);}` | ![0orangered-1](https://github.com/StephanieMussi/leaflet-huerotate-markers/assets/44252274/f71f85a6-8b64-4c6f-947c-cc7aa015430a) |
  
### References:
  
- Leaflet, an open-source JavaScript library for mobile-friendly interactive maps: https://leafletjs.com/
- W3 Schools HTML Color Names: https://www.w3schools.com/colors/colors_names.asp
