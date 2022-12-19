---
Title: Hobby
Description: Page about my hobby
---

Min hobby
====================

Vet inte om jag har någon hobby, men jag tycker om att utöka mina kunskaper i svenska och engelska. Jag kan försöka memorera och översätta nya ord till svenska-engelska-ukrainska så att jag kan använda de senare.

![Red sky](image/sky_small_640x426.jpg "This is img title.")
<img src="image/camera_638x640.png" srcset="image/student-logo.png 2x" class="max-width" alt="A cartoon boy rasing right hand"/>

<picture>
    <source media="(min-width: 668px)" srcset="image/student-logo.png, image/camera_638x640.png 2x">
    <source media="(min-width: 376px)" srcset="image/tree2.jpg" alt="Trees from dbwebb">
    <img src="image/me.jpg" class="max-width" alt="Picture of Olha Bruce"/>
</picture>

<img src="image/camera.svg" alt="camera" title="cmerrrraaaa">
![This is an attempt to use svg in Markdown](image/camera.svg "SVG Image.")

# Laddar in bilden som vanligt
![Leaf](%assets_url%/img/leaf_256x256.png)
```![Leaf](%assets_url%/img/leaf_256x256.png)```
# Laddar in bilden via Cimage
```![Leaf](image/leaf_256x256.png)```
![Leaf](image/leaf_256x256.png?w=150&h=150)
![Leaf](image/leaf_256x256.png?h=250&w=50&stretch)
![Leaf](image/leaf_256x256.png?h=250&w=50&crop-to-fit)
![Leaf](image/leaf_256x256.png)
![Leaf](image/leaf_256x256.png?width=50%)
Och i våra .twig-filer är det inte svårare än såhär:
# Som vanligt
```<img class="flash-img" src="{{ assets_url }}/img/leaf_256x256.png">```
# Via Cimage
```<img class="flash-img" src="{{ base_url }}/image/leaf_256x256.png">```

## Beskärning

![Leaf](image/leaf_256x256.png?area=50,0,0,0)
![Leaf](image/leaf_256x256.png?area=0,50,0,0)
![Leaf](image/leaf_256x256.png?area=0,0,50,0)
![Leaf](image/leaf_256x256.png?area=0,0,0,50)

## Crop

![Leaf](image/leaf_256x256.png?crop=50,50,100,100)

![Leaf](image/leaf_256x256.png?crop=50,50,125,125)

![Leaf](image/leaf_256x256.png?crop=50,50,50,50)

## Kvalité & filstorlek

![Leaf](image/leaf_256x256.png?width=50%&save-as=jpg)
![Leaf](image/leaf_256x256.png?width=50%&save-as=png)
![Leaf](image/leaf_256x256.png?width=50%&save-as=gif)

![Leaf](image/leaf_256x256.png?save-as=jpg&width=50%)
![Leaf](image/leaf_256x256.png?save-as=jpg&width=50%&q=50)

## Filter

![Leaf](image/leaf_256x256.png)
![Leaf](image/leaf_256x256.png?convolve=lighten)
![Leaf](image/leaf_256x256.png?convolve=darken)
![Leaf](image/leaf_256x256.png?blur)
![Leaf](image/leaf_256x256.png?f=grayscale)
![Leaf](image/leaf_256x256.png?f=brightness,50)
![Leaf](image/leaf_256x256.png?f=contrast,50&nc&v)

# En responsiv bild med hjälp av cimage

<picture>
    <source media="(min-width: 668px)" srcset="%base_url%/image/sheep.jpg">
    <source media="(min-width: 376px)" srcset="%base_url%/image/sheep-small-landscape.jpg">
    <img src="%base_url%/image/sheep-small-portrait.jpg" class="max-width" alt="sheep">
</picture>

![Sheep](image/sheep.jpg)

<a href="%base_url%/image/sheep.jpg" target="_blank">
    <picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/sheep.jpg">
        <img src="%base_url%/image/sheep.jpg&w=667" alt="A sheep">
    </picture>
</a>

## Responsive Video
<div class=embed-container>
<iframe src="https://www.youtube.com/embed/mDUdF1SdvjE" title="YouTube video player" frameborder="0" allowfullscreen></iframe>
</div>