# Lambda School Guest Lecture
## Supervised Machine Learning with Numerical + Text-Based Features

In this project, we will explore two datasets that contain career level data (via FanGraphs.com) and pitch style descriptions (via BrooksBaseball.net) for 758 MLB starting pitchers that threw more than 100 innings between 2010-2018 as well as an indication of whether or not the pitcher got Ulnar Collateral Ligament Reconstruction commonly referred to as Tommy John Surgery.

We will compare the performance of a simple decision tree model trained on:
- The career level data only (all numerical features)
- The career level data and pitch style descriptions transformed as topic proportions in a Latent Diriclet Allocation (LDA) model

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

The easiest way to install the project requirements is to create a virtual environment, clone the repo, and install the requirements.txt file. 

- conda create -n yourenvname python=3.6 anaconda

- source activate yourenvname

- pip install -r requirements.txt
