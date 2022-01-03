# Machine-Learning-in-mouse-tracking
For our exam project in Perception and Action, Cognitive Science Aarhus University. 

## Abstract
Mouse-tracking is a method used to assess real-time cognitive processing in psychological tasks through the movement of a computer mouse. Research have shown that movements are continuously updated by the underlying cognitive process, making mouse-tracking an easily accessible window into a decision-making process. However, the lack of a “best practice” within the flexible methodology of mouse-tracking has raised concerns about lack of reproducibility and possibilities of p-hacking. Maldonado et al. (2019) proposes a machine-learning based framework utilising principal component analysis and a pre-trained linear-discriminant-analysis classifier as a proposal to a standardised method of analysis. This paper investigates the generalisability of this framework by replicating the classic phonological similarity study by Spivey et al. (2005), re-applying the framework to this newly produced data and investigates possible improvements of the framework. Results show that the framework does not generalise well and performs poor classifications of the replication data, with an area under the receiver operant characteristic curve of only 0.575 with 95% CI [0.564, 0.585]. This paper proposes a more thorough investigation into number of principal components to further improve the model, with preliminary results by using a stopping rule of 95% variance retained suggesting differing number of principal components based on whether spatial or/and temporal information are used. 

## Content
This repository contains
  1. Data from Maldonado et al. (2019) and their script which we slighly modified. 
  2. Data from our replication of (Spivet et al., 2005)
  3. Python and R scripts for preprocessing and analysis of Spivey et al. (2005). 
  4. Highlighted and important figures. 


## Contact Information
Authors: Sigurd Fyhn Sørensen (202006317@post.au.dk) & Niels Aalund Krogsgaard (202008114@post.au.dk) 
