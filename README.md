# SGBS

This Repository is a reference implementation of *Simulation-Guided Beam Search for Neural Combinatorial Optimization*.

<br>

## Problems
* Traveling Salesperson Problem (TSP)  
* Capacitated Vehicle Routing Problem (CVRP)  
* Flexible Flow Shop Problem (FFSP)   

<br>

## Usage

### 🌱 TSP

#### SGBS
> cd ./TSP/2_SGBS  
> python3 test.py

#### SGBS+EAS
> cd ./TSP/3_SGBS+EAS  
> python3 test.py

### 🌱 CVRP

#### SGBS
> cd ./CVRP/2_SGBS  
> python3 test.py

#### SGBS+EAS
> cd ./CVRP/3_SGBS+EAS  
> python3 test.py

### 🌱 FFSP

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
**sgbs-neurips/sgbs-neurips** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
