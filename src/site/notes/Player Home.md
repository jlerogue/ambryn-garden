---
{"dg-publish":true,"permalink":"/Player Home/","tags":["gardenEntry"]}
---

obsidian://open?vault=Ambryn&file=Obsidian%2FImages%2F20230823_195912850_iOS.png


For markdown images, use ![AltText|100x100](https://bnz06pap002files.storage.live.com/y4m3a_w3rELzTeM8JygEsN6BXLemZiQXlXTRPJ1EsX5weWkwhotpZet9VMTViYWgcbJm_HJa6JJHpjH4qPkCpNI3VXOFGgPnGbrPaAmkhQOpnkMukMVrvydF8nhLg-7NEkc7bNbGXCRFi7ZDTk4uQajGetshsQwmGRwzyd9PDLCZQHUh0pqzs-yjurSpEHzwmddKaHdKaQGoXYuBa7_Pqjn7_k3zeD_KzoZfDASj0bX-KI?encodeFailures=1&width=219&height=219)

For embeds, use ![[z_Assets/Misc/ImagePlaceholder.png\|100x100]]

To have the image scale according to its aspect ratio, omit the height ![[z_Assets/Misc/ImagePlaceholder.png\|200]]

[[Characters/Stonephalanx Characters/Bailor\|Bailor]]

---
dg-publish: true
---

```leaflet  
### Tutorial: [https://youtu.be/54EyMzJP5DU](https://youtu.be/54EyMzJP5DU)  
### id must be unique  
id: Obsidian/Maps/Ambryn Continent Map.jpg
### Lock pins so they can't be moved  
lock: true  
### If true, view of map will recenter as you zoom out.  
recenter: true  
### If true, disables mouse scroll for zomming in and out of a map. Button controls still work.  
noScrollZoom: true  
image: [[Z.Obsidian/Maps/Ambryn Continent Map.jpg]]
### Map Pixel Height x 1 / (Pixels between Bar Scale / 100)  
### Map Pixel Width x 1 / (Pixels between Bar Scale / 100)  
### Note that this formula requires adjustments depending on your map. The idea is to determine the number of units between your bar scale. We divide by 100 here because my bar scale measures in 100 units. If your maps scale bar measures in units of 50 them you should divide by 50 instead. The idea is to calculate how many pixels are equal to 1 unit.  
### Bounds is entered as [Height, Width]  
bounds: [[0,0], [1815.07, 2805.48]]  
height: 900px  
width: 85%  
### This sets where the map starts by default. Set it to the middle (half) of your bounds.  
lat: 907.53  
long: 1402.74  
### 0 is no zoom. Negative zoom steps away from the map. Positive zoom steps towards the map.  
minZoom: -1
### Max zoom is 18.  
maxZoom: 16  
### Hover mouse over the Reset Zoom icon to see your current zoom level.  
defaultZoom: -1.5
### How far it zooms in or out with each step. Can be in decimals.  
zoomDelta: 0.5  
### This is a string so can be any text. Change it to match your maps measurement scale.  
unit: miles  
scale: 1  
darkMode: false  
```


