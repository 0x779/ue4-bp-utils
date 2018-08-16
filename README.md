# Unreal Engine 4 Blueprint utilities

These are some Blueprint utilities that I've used over the years. I'm releasing them in the hopes that they'll help you in your game making. Some are working fine, some need a little tinkering.

I'll add more as time passes.

## Color
### Hex to RGB
This converts hex color codes (with or without the pound) to a linear color structure.
![](https://i.imgur.com/yFD222h.png)
### Kelvin to RGB
This converts temperature units (Kelvin) to a linear color structure.
![](https://i.imgur.com/IDDpqz9.png)

## Photometry
### B-V to Kelvin
This converts the star color index to Kelvin (which then can be used to be converted to a linear color structure with **KelvinToRGB** (works good enough, but needs to be thoroughly tested).
![](https://i.imgur.com/KhJUQnj.png)
## Astronomy
### RADEC to cartesian
This converts right ascension and declination to a vector (right-hand).
![](https://i.imgur.com/YYYRXZa.png)
