
# Welcome
Welcome to *WorldPop Population Modelling Training Manual, vol I*. This is an open book designed to provide in-depth guide and understanding to researchers and users of WorldPop small area population datasets on how the underlying statistical methods are developed and implemented across various contexts. It complements the *WorldPop Book of Methods* by going a step further to demonstrate the step-by-step processes of ‘how-to-do’ rather than ‘how-it-is-done’ by providing relevant background knowledge and practical examples.
The manual which was developed by the WorldPop Research Group within the School of Geography and Environmental Science at the University of Southampton, is made up of 11 modules tailored to meet the needs of diverse audience. Although mainly based on R statistical programming language, the manual is designed to accommodate users at various levels of expertise and backgrounds by including very basics of R and statistical methods, in addition to more complex methodologies within the later modules.
The manual is licensed under a [Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0) License](https://creativecommons.org/licenses/by-nd/4.0/), and the lead developer and compiler was [Layna Dennett](https://www.southampton.ac.uk/people/5xq75k/miss-layna-dennett), with the support of [Somnath Chaudhuri](https://www.worldpop.org/team/dr-somnath-chaudhuri/), under the coordination and supervision of [Chris Nnanatu](https://www.worldpop.org/team/chris_nnanatu/), while oversight was provided by [Andrew Tatem](https://www.worldpop.org/team/andy_tatem/).
 
To cite this manual, please use:
WorldPop. 2025. *WorldPop Population Modelling Training Manual, vol I*. WorldPop, University of Southampton.(2025) (https://wpgp.github.io/pop_training_manual/)

[![DOI](https://zenodo.org/badge/1017646085.svg)](https://doi.org/10.5281/zenodo.15862118)

# Acknowledgements

We express our profound gratitude to key individuals and organisations who played various roles in making this population modelling training manual a reality.
We appreciate [Layna Dennett](https://www.southampton.ac.uk/people/5xq75k/miss-layna-dennett) for doing a fantastic job leading the development and compilation of the training manual, and we are very grateful to [Somnath Chaudhuri](https://www.worldpop.org/team/dr-somnath-chaudhuri/) for all the essential technical supports he provided throughout the development and compilation of the training manual.
We thank [Chris Nnanatu](https://www.worldpop.org/team/chris_nnanatu/) for initiating the project and providing coordination and supervision throughout. Additionally, we thank [Ortis Yankey](https://www.worldpop.org/team/ortis_yankey/) and [Assane Gadiaga](https://www.worldpop.org/team/assane_gadiaga/) for their various contributions, and we are grateful to [Heather Chamberlain](https://www.worldpop.org/team/heather_chamberlain/) and [Sarchil Qadar](https://www.worldpop.org/team/sarchil_qader/) for providing some images used in the manual. The manual benefited immensely from reviews and valuable feedback from [Gianluca Boo](https://www.worldpop.org/team/gianluca-boo/), [Amy Bonnie](https://www.worldpop.org/team/amy_bonnie/), [Iyanuloluwa Olowe](https://www.worldpop.org/team/iyanuloluwa-olowe/), and [Andrew Tatem](https://www.worldpop.org/team/andy_tatem/), and we appreciate them for this.
Finally, this manual would not have been a reality without the demographic datasets provided by Cameroon National Institute of Statistics (CNIS), and we thank **Mr Anaclet Desire Dzossa** specially for his immense support.  And we wish to acknowledge the continued generous financial supports of our key funding partners:  the Bill & Melinda Gates Foundation, the United Nations Population Fund (UNFPA), Geo-Referenced Infrastructure and Demographic Data for Development (GRID3), the Foreign, Commonwealth & Development Office (FCDO), and the World Bank, as well as other United Nations agencies. 



# Book Contents

- **Module 1: Basics of R Programming**  
  <!-- Learn the foundation skills needed to begin using R for data analysis and spatial modelling. -->
   Ideal for individuals who have little to no experience with R, or who would like a reminder. It contains the basics on getting started with R, beginning with how to install R on your computer and understanding the key aspects of the software. Lastly, Module 1 gives an introduction to using R, including information on the basic operations, functions, and data structures.
  
- **Module 2: Working with Data Frames** 
  Focuses on working with data frames, including how to install data into the R environment, basic data wrangling methods and data visualisation.

- **Module 3: Working with Spatial Data in R**
  Introduction spatial data, with an overview of the different types at the start and how to work with them. This module also includes some basic GIS/geoprocessing methods in R, and expands on the data visualisation methods from Module 2, accounting for the spatial aspect to the data.

- **Module 4: Introduction to Statistical Modelling with Implementation in R**
  Introduction statistical modelling and the implementation of the different methods into R. Additionally, it covers different methods of making predictions from the models, model selection, and cross-validation.

- **Module 5: Probability Theory and Applications**
  Introduction to probability theory, focusing on the methods and applications rather than the code. This module covers the foundations of both theoretical and experimental probability, the axioms of probability, and more detailed explanations of joint and conditional probability, with simple, easy-to-follow examples throughout.

- **Module 6: Bayesian Statistical Inference**
  Covers the basics to more in-depth Bayesian statistical inference, including Bayes’ rule (also called Bayes’ theorem), likelihoods, the prior distribution, and the posterior distribution.

- **Module 7: Introduction to Small Area Population Estimation and Modelling (SAPEM)**
  Focuses on small area population estimation, with information on both direct estimation and indirect estimation, where the latter includes both top-down and bottom-up methodology, with the relevant code given in the Book of Methods.

- **Module 8: Bayesian Hierarchical Population Modelling in R**
  Expands on the Bayesian hierarchical population modelling covered in earlier modules, focusing instead on the methods with spatial data. It introduces the different key data sources, methods for covariate extraction, exploratory analysis, and model setup. The remainder of the module briefly covers the STAN (MCMC) and goes into detail for the INLA-SPDE approach to Bayesian hierarchical modelling.

- **Module 9: Model Fit Checks and Cross-Validation**
  Expands on methods discussed in earlier modules, detailing on model assumption checking methods, and different techniques for model selection. Additionally, this module covers cross-validation methods in more detail than in Module 4.

- **Module 10: Population Prediction and Uncertainty Quantification**
  Looks at population prediction methods and the associated uncertainty quantification, starting with covariate stacking. It also covers posterior distribution simulation, aggregation to area units of interest, and grid cell/level prediction.

- **Module 11: Age-Sex Disaggregation**
   The final module and covers disaggregation of population totals by age-sex proportions for instances where there is age-sex data available as well as instances where there is not available.


