# SGBS

This Repository is a reference implementation of *Simulation-Guided Beam Search for Neural Combinatorial Optimization*.

<br>

## Problems
* Traveling Salesperson Problem (TSP)  
* Capacitated Vehicle Routing Problem (CVRP)  
* Flexible Flow Shop Problem (FFSP)   

<br>

## Usage

### š± TSP

#### SGBS
> cd ./TSP/2_SGBS  
> python3 test.py

#### SGBS+EAS
> cd ./TSP/3_SGBS+EAS  
> python3 test.py

### š± CVRP

#### SGBS
> cd ./CVRP/2_SGBS  
> python3 test.py

#### SGBS+EAS
> cd ./CVRP/3_SGBS+EAS  
> python3 test.py

### š± FFSP

To run SGBS and SGBS+EAS for FFSP, you have to download and unpack FFSP.tar.gz first.  
See *FFSP trained model & dataset* section.  

#### SGBS
> cd ./FFSP/2_SGBS  
> python3 test_ffsp20(50/100).py

#### SGBS+EAS
> cd ./FFSP/3_SGBS+EAS  
> python3 test_ffsp20(50/100).py

<br>

## FFSP trained model & dataset
Download FFSP trained model and dataset file from https://drive.google.com/file/d/1TdkeErG1FCUMxoe8ENpxiWwUopPIUikb/view?usp=sharing.  
Move FFSP.tar.gz into your root folder and unpack it.  
> tar -xvzf FFSP.tar.gz

<br>

## Language and Libraries
python 3.8.6  
torch 1.11.0

<!--
**sgbs-neurips/sgbs-neurips** is a āØ _special_ āØ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- š­ Iām currently working on ...
- š± Iām currently learning ...
- šÆ Iām looking to collaborate on ...
- š¤ Iām looking for help with ...
- š¬ Ask me about ...
- š« How to reach me: ...
- š Pronouns: ...
- ā” Fun fact: ...
-->
