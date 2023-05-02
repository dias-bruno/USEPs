# Urban Socio-Environemental Patterns (USEPs): classification methodology and data access

*Bruno Dias dos Santos* (1), *Carolina Moutinho Duque de Pinho* (2), *Antonio Paéz* (3) and *Silvana Amaral* (1)

(1) National Institute for Space Research, São José dos Campos – Brazil, {bruno.santos, silvana.amaral}@inpe.br; 

(2) Federal University of ABC, Santo André – Brazil, carolina.pinho@ufabc.edu.br; 

(3) McMaster University, Hamilton – Canada, paezha@mcmaster.ca.

[![DOI](https://zenodo.org/badge/630576394.svg)](https://zenodo.org/badge/latestdoi/630576394)

This Git repository contains the shapefile files resulting from a scientific research project focused on identifying and classifying urban and socio-environmental patterns in the Brazilian Amazon cities of Santarém and Cametá, located in the state of Pará. The research was developed within the Masters Program in Remote Sensing of the National Institute for Space Research.

To reproduce the classification methodology, follow the below steps:

*Code 1:* Run this code twice, once for the environmental dimension file (base_env) and once for the urban morphological dimension (base_urb). This code performs a treatment and selection of variables and performs an unsupervised classification to identify clusters in each dimension of analysis.

*Code 2:* After identifying the clusters of the environmental (cluster_env) and urban morphological (cluster_urb) dimensions, run this code to apply a new unsupervised classification and identify the final clusters (USEPs) that integrate the results obtained in the previous step.

*Code 3:* With the final clusters in hand, run this notebook to socioeconomically characterize the USEPs identified previously.
For any questions, please contact bruno.santos@inpe.br.
