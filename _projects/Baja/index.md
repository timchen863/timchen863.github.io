---
layout: post
title: Baja Off-Road Illini SAE
description: As part of the suspension and chassis team for Baja SAE, I designed and analyzed mechanical components for an off-road racing vehicle. I created CAD models in PTC Creo for parts including tie rods, an exhaust manifold, and a shock absorber, and performed Finite Element Analysis (FEA) in ANSYS and Fusion 360 to evaluate structural performance under dynamic off-road loads.
skills: 
 - Soldering
 - Welding
 - PTC Creo
 - Autodesk Fusion 360
 - FEA
 - Ansys

main-image: /Baja.jpg
---

---
{% include youtube-video.html id="7PXh7vJ46tg" autoplay="true" %}
---

## Design Constraints

- Limited space within the Baja chassis
- High dynamic loads from off-road driving
- Manufacturability using available fabrication methods
- Integration with existing suspension components

## Exhaust Manifold
{% include image-gallery.html images="EM1.png, EM2.png, EM3.png" height="300" %}
<br>
## Shock Absorber
{% include image-gallery.html images="sa1.png" height="400" %}
---

## Finite Element Analysis
FEA simulation was used to analyze the thermal behavior of the brake rotor during braking.
{% include image-gallery.html images="br.png" height="400" %}
- **Max Temp:** 546.6°C  
- **Min Temp:** 30.3°C  
### Observations
- Outer rotor surfaces experience rapid heating
- Inner hub remains cooler, acting as a thermal sink
- Temperature gradient aligns with expected rotor behavior under braking loads

<!--## Embedding youtube video
The second video has the autoplay on. copy and paste the 11-digit id found in the url link. <br>
*Example* : https://www.youtube.com/watch?v={**MhVw-MHGv4s**}&ab_channel=engineerguy
{% include youtube-video.html id="MhVw-MHGv4s" autoplay= "false"%}
{% include youtube-video.html id="XGC31lmdS6s" autoplay = "true" %}

you can also set up custom size by specifying the width (the aspect ratio has been set to 16/9). The default size is 560 pixels x 315 pixels.  

The width of the video below. Regardless of initial width, all the videos is responsive and will fit within the smaller screen.
{% include youtube-video.html id="tGCdLEQzde0" autoplay = "false" width= "900px" %}  

<br>

## Adding a hozontal line
---

## Starting a new line
leave two spaces "  " at the end or enter <br>

## Adding bold text
this is how you input **bold text**

## Adding italic text
Italicized text is the *cat's meow*.

## Adding ordered list
1. First item
2. Second item
3. Third item
4. Fourth item

## Adding unordered list
- First item
- Second item
- Third item
- Fourth item

## Adding code block
```ruby
def hello_world
  puts "Hello, World!"
end
```

```python
def start()
  print("time to start!")
```

```javascript
let x = 1;
if (x === 1) {
  let x = 2;
  console.log(x);
}
console.log(x);

```

## Adding external links
[Wikipedia](https://en.wikipedia.org)


## Adding block quote
> A blockquote would look great if you need to highlight something


## Adding table 

| Header 1 | Header 2 |
|----------|----------|
| Row 1, Col 1 | Row 1, Col 2 |
| Row 2, Col 1 | Row 2, Col 2 |

make sure to leave aline betwen the table and the header-->
