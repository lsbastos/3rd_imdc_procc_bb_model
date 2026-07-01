<p align="center">
  <img src="img/home_imdc.svg" alt="Sprint Planning" width="800" height="200">
</p>


 <strong> 1. Team and Contributors</strong> 
* Leo Bastos (PROCC/Fiocruz)
* Lais Picinini Freitas (ENSP/Fiocruz)
* Ramila Alencar (ENSP/Fiocruz)
* Daniele Ferreira (PROCC/Fiocruz)


<strong> 2. Repository Structure </strong>

To do

<strong> 3. Libraries and Dependencies </strong>

R and R-INLA

<strong> 4. Data and Variables </strong>

* Which datasets and variables were used?
  <p>Dengue and Chikungunya datasets</p>
* How was the data pre-processed?
  <p>Data from ES at years 2020 and 2021 were removed!</p>
* How were the variables selected? Please point to the relevant part of the code.
  <p>No data selection involded.</p>

<strong>5. Model Training </strong> 

* Description of how the model was trained. If applicable, describe any hyperparameter optimization techniques used.
  <p> It is a negative binomial model with week and year random effects by macro region. </p>

* Please specify where the code for training and generating forecasts is located, and provide instructions on how to run it.
  <p>To do.

<strong> 5. Data Usage Restriction </strong>

* Describe how you handled the requirement of using only data up to EW 25 of the current year to generate predictions from EW 41 of the same year to EW 40 of the next year.
<p> NAs were added, and there is no covariates in the modelling. </p>

<strong> 6. Predictive Uncertainty </strong> 
How are your prediction intervals computed? 
<p>Using Monte Carlo</p>

<strong> 7. References </strong>

Picinini Freitas et al. (2025) A statistical model for forecasting probabilistic epidemic bands for dengue cases in Brazil, Volume 10, Issue 4, Pages 1479-1487, Infectious Disease Modelling
<h>https://doi.org/10.1016/j.idm.2025.07.014</h>.

