## _welcome to our machine learning project_ 


* _**project officials**_:
  
| Name | 
| - | 
| [fateme davari](https://github.com/Fatemeh-davari1997) | 
| [mahdi nouraie](https://github.com/MahdiNouraie) |
| [hamoon sajadi](https://github.com/hamoonsj) |
| [hosein jamshidian](https://github.com/hosein-jamshidian) |
  
### _framework_:

   In this project, we want to working with 3 categories of data, which are _**FreeSolv**_ is _**Regression**_ and _**SIDER**_ , _**Tox21**_ is _**Classification**_ type.
The goal is to provide an appropriate and preferably optimal algorithm for the cleaned data so that after running on the data we can have a function that guesses the labels with the least generalization error.
  
  ---
### _Freesolve_:
   ```
   a database of experimental and calculated hydration free energies.
   ```
* _ABSTRACT_:
 
  - This work provides a curated database of experimental and calculated hydration free energies for small neutral molecules in water, along with molecular structures, input files, references, and annotations. We call this the Free Solvation Database, or _**FreeSolv**_. Experimental values were taken from prior literature and will continue to be curated, with updated experimental references and data added as they become available. Calculated values are based on alchemical free energy calculations using molecular dynamics simulations. These used the GAFF small molecule force field in TIP3P water with AM1-BCC charges. Values were calculated with the GROMACS simulation package, with full details given in references cited within the database itself. This database builds in part on a previous, 504-molecule database containing similar information. However, additional curation of both experimental data and calculated values has been done here, and the total number of molecules is now up to 643. Additional information is now included in the database, such as SMILES strings, PubChem compound IDs, accurate reference DOIs, and others.
  ---

### _SIDER_:
```
a database of drugs and side effects
```
* _ABSTRACT_:
   
   - Unwanted side effects of drugs are a burden on patients and a severe impediment in the development of new drugs. At the same time, adverse drug reactions (ADRs) recorded during clinical trials are an important source of human phenotypic data. It is therefore essential to combine data on drugs, targets and side effects into a more complete picture of the therapeutic mechanism of actions of drugs and the ways in which they cause adverse reactions. To this end, we have created the _**SIDER**_ ('Side Effect Resource', http://sideeffects.embl.de) database of drugs and ADRs. The current release, SIDER 4, contains data on 1427 drugs, 5880 ADRs and 140 064 drug-ADR pairs, which is an increase of 40% compared to the previous version. For more fine-grained analyses, we extracted the frequency with which side effects occur from the package inserts. This information is available for 39% of drug-ADR pairs, 19% of which can be compared to the frequency under placebo treatment. SIDER furthermore contains a data set of drug indications, extracted from the package inserts using Natural Language Processing. These drug indications are used to reduce the rate of false positives by identifying medical terms that do not correspond to ADRs.
--- 
### _Tox21_:
 ```
 robotic platform for assessment of environmental chemicals - from vision to reality.
 ```
* _ABSTRACT_:

    - its establishment in 2008, the US Tox21 inter-agency collaboration has made great progress in developing and evaluating cellular models for the evaluation of environmental chemicals as a proof of principle. focusing  on the areas of modulation of nuclear receptors and stress response pathways.
 
------ 

## _**Dataset Details**_:
| Category | Dataset | Datatype | Task type | #Task | #Compounds | Rec-Split | Rec-Metric |
| - | - | - | - | - | - | - | - |
| physical chemistry | [Freesolv](https://raw.githubusercontent.com/hhaji/Applied-Machine-Learning/master/Projects/Projects-Fall-2021/Data/freesolv.csv) | SMILES | Regression | 1 | 642 | Random | RMSE |
| phisiology | [SIDER](https://raw.githubusercontent.com/hhaji/Applied-Machine-Learning/master/Projects/Projects-Fall-2021/Data/sider.csv) | SMILES | Classification | 27 | 1427 | Random | ROC-AUC |
| phisiology | [Tox21](https://raw.githubusercontent.com/hhaji/Applied-Machine-Learning/master/Projects/Projects-Fall-2021/Data/tox21.csv) | SMILES | Classification | 12 | 7831 | Random | ROC-AUC |
