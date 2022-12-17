## Resize-Image-Interpolation
How image resize function working ?
## Introduce 
* Resize image in interpolation 
* Result comparing between code from scratch with opencv package  mode = INTER_NEAREST and mode = INTER_LINEAR

## Comparison
New Dimention = 0.7 * Old Dimention
* Original Image
<div align="center">
<br>
<img src="origin.jpg" width="400">
<p>Original Image</p>
</div

* NEAREST NEIGHBOR INTERPOLATION  (Orgin-Resized)

<div align="center">
<br>
<img src="origin.jpg" width="400"></img>
<img src="nearest_color.png" width="400"></img>
<img src="origin.jpg" width="400"></img>
<img src="nearest_gray.png" width="400"></img>
<p>
</div>

* BILINEAR INTERPOLATION (Orgin-Resized)
<div align="center">
<br>
<img src="origin.jpg" width="400"></img>
<img src="linear_color.png" width="400"></img>
<img src="origin.jpg" width="400"></img>
<img src="linear_gray.png" width="400"></img>
<p>
</div>

* DIFF NEAREST NEIGHBOR <-> OPENCV (Color-Gray)
<div align="center">
<br>
<img src="nearest_color_diff.png" width="400"></img>
<img src="nearest_gray_diff.png" width="400"></img>
<p>
</div>

* DIFF LINEAR <-> OPENCV (Color-Gray )
<div align="center">
<br>
<img src="linear_color_diff.png" width="400"></img>
<img src="linear_gray_diff.png" width="400"></img>
<p>
</div>

