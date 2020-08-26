# Heat Exchanger Network Design
This module contains two Jupyter Notebooks. <br> The first notebook provides relevant data to the user to choose optimum ΔTmin for Heat Exchanger Network Design by considering the trade-off between Minimum Area and Utility Requirement. <br> Based on the data and costing information, the user selects an optimum ΔTmin and uses it in the second Jupyter Notebook. <br> A corressponding Heat Exchanger Network is designed with Minimum Possible Area and Maximum Energy Recovery.

<br>
<h3>Input for finding Optimum Minimum Temperature Difference: </h3><br>
<br>
An Excel file containing: <br>
<ul>
  <li> Stream Information</li>
  <li> Supply Temperature (°C)</li>
  <li> Target Temperature (°C)</li>
  <li> Heat Load (kW)</li>
</ul> <br>
Overall Heat Transfer Coefficient (W/m2.K) prompted by the Jupyter Notebook <br> 
<br>
<h3> Output to choose Minimum Temperature Difference: </h3> <br>
<ul>
  <li> Graph of Minimum Area vs Minimum Utility Required </li>
  <li> Graph of Minimum Area vs ΔTmin </li>
  <li> Graph of Minimum Utility vs ΔTmin </li>
</ul> <br>
An Excel file of 100 rows containing: <br>
<ul>
  <li> ΔTmin (°C) </li>
  <li> Pinch Temperature (°C) </li>
  <li> Ideal Minimum Hot Utility Required (kW) </li>
  <li> Ideal Minimum Cooling Utility Required (kW) </li>
  <li> Ideal Minimum Area Required (m^2) </li>
 </ul> <br>
If the user has costing information, he/she can make a sound decision to choose optimum ΔTmin.<br>
<br>
<h3> Input for Heat Exchanger Network Design: </h3> <br>
An Excel file containing: <br>
<ul>
  <li> Stream Information</li>
  <li> Supply Temperature (°C)</li>
  <li> Target Temperature (°C)</li>
  <li> Heat Load (kW)</li>
</ul> <br>
ΔTmin (°C) prompted by the Jupyter Notebook <br>
<h3> Output for Heat Exchanger Network Design: </h3> <br>
<ul>
  <li> Combined Composite Curve </li>
  <li> Grand Composite Curve </li>
  <li> Pinch in the Grid Representation </li>
  <li> Temperature Interval Diagram </li>
  </ul> <br>
  An Excel file containing: <br>
  <ul>
  <li> Problem Table algorithm for Pinch Analysis </li>
  <li> Table to generate Hot Composite Curve </li>
  <li> Table to generate Cold Composite Curve </li>
  <li> Table for Area Targetting of Heat Exchanger Network Design </li>
  </ul> <br>
<br>
<h3> Assumptions </h3> <br>
<ul>
  <li> Heat Capacity Flow Rates (FCp) are constant and doesn't vary from Supply Temperature to Target Temperature. </li>
  <li> Overall Heat Transfer Coefficient (U) is same for all the stream matches. </li>
  <li> The pressure drop a stream experiences while going through a heat exchanger is within its permissible limit and no extra compressor is required. </li>
  <li> All the streams in heat exchanger undergo pure countercurrent flow </li>
  </ul>
<br>
<br>
<h3> About the Author: </h3> <br>
This Github repository is made by Abhishek Kundu, currently a final year student pursuing Bachelor of Chemical Engineering course at Institute of Chemical Technology, Mumbai, India. He can be contacted on his LinkedIn profile <a href = "https://www.linkedin.com/in/abhishek-kundu-a77356166"> here </a> for feedback and criticism. 
