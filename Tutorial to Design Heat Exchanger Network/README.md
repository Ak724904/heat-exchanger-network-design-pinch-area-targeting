<h1> Steps to Design Heat Exchanger Network </h1> <br>
<br>
<ol>
  <li> Input Data in 'Input Sheet' Excel file </li>
  <li> Run the 'Design for Heat Exchanger Network' Jupyter Notebook. </li>
  <li> Enter a ΔTmin (in our case 20°C) value selected by optimizing the cost parameter. </li>
  <li> Make appropriate divisions in the 'Pinch in the Grid Representation' from the 'minimum_area_calculation' Table for Area Targetting. </li>

  <li> Place appropriate Heat Exchangers, Coolers, and Heaters to complete the Design. </li>
</ol> <br>

![Pinch in the grid representation](https://user-images.githubusercontent.com/63314951/91294400-11176a00-e7b7-11ea-874c-4fe8a128ddae.png)

![Area Targetting Table](https://user-images.githubusercontent.com/63314951/91294039-8afb2380-e7b6-11ea-9c07-bb6c4b914067.PNG)

![Heat Exchanger Network Step 1](https://user-images.githubusercontent.com/63314951/91291987-85500e80-e7b3-11ea-8fdd-d4c735bd58c4.PNG) <br>

![Heat Exchanger Network Step 2](https://user-images.githubusercontent.com/63314951/91292530-48384c00-e7b4-11ea-9b5b-10fd25086571.PNG) <br>


<b> Note: </b> Our particular selection of ΔTmin makes the problem a threshold problem and hence, no heater or cooler is required. <br>
If the selected ΔTmin is higher than the threshold ΔTmin, one should deploy only heating utilities in the 'Hot End' and only cooling utilities in the 'Cold End.' <br>
Violation of this rule would lead to unnecessary energy wastage. 
