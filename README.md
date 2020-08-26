# Selection of Optimum ΔTmin and Area Targeting of Heat Exchanger Network Design by Classical Pinch Method
This project contains two Jupyter Notebooks for design of a Heat Exchanger Network. <br> The first Jupyter Notebook provides relevant data to the user to choose optimum Minimum Temperature Difference by considering the trade-off between Heat Exchanger Area and Utility Requirement. <br> Based on the data and costing information, the user selects an optimum ΔTmin and a corresponding Heat Exchanger Network is designed with Minimum Possible Area without compromising on the Maximum Possible Energy Recovery in the second Jupyter Notebook.
<br>
<h3>Input for finding Optimum Minimum Temperature Difference: </h3>
<br>
An Excel file containing: <br>
<ul>
  <li> Stream Information</li>
  <li> Supply Temperature (°C)</li>
  <li> Target Temperature (°C)</li>
  <li> Heat Load (kW)</li>
</ul> <br>
Overall Heat Transfer Coefficient (W/m2.K) prompted by the Jupyter Notebook 
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
If the user has costing information, he/she can make a sound decision to choose optimum ΔTmin.
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
  <li> Table for Area Targeting of Heat Exchanger Network Design </li>
  </ul>
<br>
<h3> Assumptions </h3> <br>
<ul>
  <li> Neither of the streams' Heat Capacity Flow Rate (FCp) vary from the Supply Temperature to the Target Temperature. </li>
  <li> Overall Heat Transfer Coefficient (U) is constant regardless of the stream matches. </li>
  <li> The pressure drop a stream experiences while going through a heat exchanger is within its permissible limit and no extra compressor is required. </li>
  <li> All the streams in heat exchanger undergo pure countercurrent flow. </li>
  </ul>
<br>
<h3> References </h3>
<br>
<ul>
<li>The Pinch Design Method for Heat Exchanger Networks- <i> B. Linnhoff </i> and <i> E.Hindmarsh </i> Chemical Engineering Science Vol.38, No. 5, pp. 745-763, 1983 </li> <br>
<li> Cost Optimum Heat Exchanger Networks-I. Minimum Energy and Capital Using Simple Models for Capital Cost- <i> B. Linnhoff </i> and <i> S. Ahmad </i> Computers Chem. Eng. Vol. 14, No. 7, pp.729-750, 1990 </li>
</ul>
<br>
<h3> About the Author: </h3> <br>
This Github repository is made by Abhishek Kundu, currently a final year student pursuing Bachelor of Chemical Engineering course at Institute of Chemical Technology, Mumbai, India. He can be contacted on his LinkedIn profile <a href = "https://www.linkedin.com/in/abhishek-kundu-a77356166"> here </a> for feedback and criticism. 

