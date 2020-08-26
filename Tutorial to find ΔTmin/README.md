<h1>Steps to find Optimum ΔTmin </h1>
<br>
<br>
<ol>
  <li> Fill the inputs in the 'Input Sheet' Excel file with appropriate units. We have taken data from <i> B.Linhoff and S.Ahmad March 1990 </i> Fig 2. </li>
  <li> Run the Jupyter Notebook 'Optimization of ΔTmin.' </li> 
  <li> Input the Overall Heat Transfer Coefficient (U) prompted by the Jupyter Notebook </li>
  <li> Graphs of Minimum Area vs Minimum Hot Utility, Minimum Utility vs ΔTmin, Minimum Area vs ΔTmin are generated. </li>
  <li> The output is generated in the 'Optimization of ΔTmin' Excel Sheet. </li> 
  <li> By adding an extra column in the excel sheet by knowing the cost of Heat Exchanger as a function of Area and cost of Hot Utility and Cold Utility per unit, one can select ΔTmin which has minimum total cost. </li>
  <li> In our example, we have assumed the plant lifetime to be 10 years and area of heat exchanger to be Rs 19 per sq.metre. This makes the cost of heat exchanger to be Rs 1.9 per sq.metre per year. The cost of hot utility and cold utility are assumed to be Rs 2 and Rs 0.2 per kW.year respectively. Appropriate changes can be made by the user in his respective Excel Sheet. </li>
  <li> A graph of Total Cost vs ΔTmin is plotted, which shows the minimum value of Total Cost to be at ΔTmin = 20°C </li>
  </ol>

![Cost vs DeltaTmin](https://user-images.githubusercontent.com/63314951/91285215-8cbeea00-e7aa-11ea-901e-9b9bdce6280a.PNG)

