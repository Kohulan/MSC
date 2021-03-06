# Molecule Set Comparator (MSC)
[![GitHub release](https://img.shields.io/github/release/zielesny/MSC.svg)](https://GitHub.com/zielesny/MSC/releases/)
[![License](https://img.shields.io/badge/License-GPL%203.0-blue.svg)](https://opensource.org/licenses/GPL-3.0)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-blue.svg)](https://GitHub.com/zielesny/MSC/graphs/commit-activity)
[![GitHub issues](https://img.shields.io/github/issues/zielesny/MSC.svg)](https://GitHub.com/zielesny/MSC/issues/)
[![GitHub contributors](https://img.shields.io/github/contributors/zielesny/MSC.svg)](https://GitHub.com/zielesny/MSC/graphs/contributors/)

- Molecule Set Comparator (MSC) is designed as an application that enables a user to do a versatile and fast comparison of large molecule sets with a unique inter-set, molecule-to-molecule comparison, for the original set and a predicted set of molecules obtained by machine learning approaches. 

- The molecule-to-molecule comparison is based on chemical descriptors, which are included in the Chemistry Development Kit (CDK), such as Tanimoto similarities, atom/bond/ring counts, and physicochemical properties like logP. The results are presented graphically and summarized by interactive histograms that can be exported in publication quality

<p align="center">
  <img src="https://github.com/zielesny/MSC/blob/master/assets/MSC_logo_.png?raw=true">
</p>

## Contents of subfolders

- ***Tutorials*** - a comprehensive step-by-step guide for the installation of MSC (*MSC_Installation_Guide.pdf*), a short introductory tutorial for MSC usage (*MSC_1.0_Tutorial.pdf*) and an application example (*MSC_Application_Example.pdf*)

- ***src*** - all Java source files and resources

- ***lib*** - open libraries used by MSC

- ***installation*** - contains the installation folder *MSC_1.0* to be copied to a local machine for MSC execution. 
  - Note, that an additional JDK download is necessary (see [instructions](https://github.com/zielesny/MSC/blob/master/installation/MSC_1.0/jdk-11.0.2/JDK%20download%20info.txt) in subdirectory *JDK-11.0.2*). 
  
  - For a guided installation look at the [installation guide](https://github.com/zielesny/MSC/blob/master/Tutorials/MSC_Installation_Guide.pdf) in the *Tutorials* folder

- ***Gradle Project for Netbeans*** - a Gradle project that can be compiled and run with Gradle, the Netbeans IDE or any other IDE that supports Gradle (JDK 11 or higher is needed)

## Running MSC

- A precompiled [fat jar file](https://github.com/zielesny/MSC/tree/master/installation/MSC_1.0/lib) (that includes all dependent libraries) is already provided in this repository. To directly use it, please have a look at the [steps](https://github.com/zielesny/MSC/blob/master/installation/MSC_1.0/README.MD) provided under the installation directory. 

- Alternatively, the MSC can be compiled using Gradle. For this, have a look at the *Gradle Project for Netbeans* folder where additional information is provided

## Citing the tool

- [K. Rajan, J.-M. Hein, C. Steinbeck and A. Zielesny, _Molecule Set Comparator (MSC) – A CDK-based open rich-client tool for molecule set similarity evaluations_, Journal of Cheminformatics (2021), 13:5](https://doi.org/10.1186/s13321-021-00485-4)

## Notes
- MSC is not modularized due to its non-modularized library dependencies.

## MSC (Screenshots)

- **Main window**
<p align="right">
  <img src="https://github.com/zielesny/MSC/blob/master/assets/MSC_1.png?raw=true">
</p>

- **Input selection**
<p align="right">
  <img src="https://github.com/zielesny/MSC/blob/master/assets/MSC_Screenshots/MSC_Input_View.JPG?raw=true">
</p>

- **Results**

<p align="right">
  <img src="https://github.com/zielesny/MSC/blob/master/assets/MSC_Screenshots/MSC_Output_View1.JPG?raw=true">
</p>

- **Pairwise visualization**

<p align="right">
  <img src="https://github.com/zielesny/MSC/blob/master/assets/MSC_Screenshots/MSC_Detail_Window2.JPG?raw=true">
</p>
