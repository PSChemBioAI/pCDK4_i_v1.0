<img width="81" height="25" alt="image" src="https://github.com/user-attachments/assets/3f63819d-1149-4290-afda-0aa6c5433c1f" /># pCDK4i_v1.0
<img src="https://github.com/PSChemBioAI/pCDK4i_v1.0/blob/main/logo.png?raw=1" width="380" align="right">

>p = predictor,
CDK4 = CDK4 enzyme,
i = inhibitor,
v1.0 = version 1.0.
>


**Machine learning-based prediction tool for CDK4 inhibitor activity**

It is a <img src="https://streamlit.io/images/brand/streamlit-mark-color.svg" alt="Streamlit Logo" width="50"/>-based [Web Application](https://pschembioai-cdk4-6.streamlit.app/). that predict the CDK4 inhibitory property (Active or Inactive) of query molecule amd displayed Predicted Probability scores. This tool also allow bacth prediction.
___
This predictive tool was developed as an integral component of the following research manuscript:
>Machine learning and multiscale molecular modeling to explore CDK4 inhibitors.

____

**How to use this?**

The **pCDK4i_v1.0** web application can be used by following [This Link](https://pschembioai-cdk4.streamlit.app/)

**1. Single Molecule Prediction:** Enter a SMILES string directly or draw the molecule using the molecular sketcher. The model will analyze the compound and provide the predicted probability.

**2. Batch Prediction:** Upload a CSV or Excel file containing the SMILES strings of multiple compounds. The application will process all molecules and return the predicted activity probability.
___

**Example Smiles:**
1. Known CDK4/6 inhibitor: CCN1CCN(Cc2ccc(Nc3ncc(F)c(-c4cc(F)c5nc(C)n(C(C)C)c5c4)n3)nc2)CC1
2. Known CDK4/6 Inactive molecule: Cc1cc(C)nc(NC(=S)N2CCN(Cc3ccc(C(F)(F)F)cc3)CC2)c1 
3. Imatinib:
Cc1ccc(NC(=O)c2ccc(CN3CCN(C)CC3)cc2)cc1Nc1nccc(-c2cccnc2)n1
______
**Applications**
- Virtual Screening of chemical compounds
- Prioritization of lead compounds based on predicted probability
- Cheminformatics-assisted compound evaluation
---
Bugs: If you encounter any bugs, please report the issue to my mail id priyankasolanki2578@gmail.com
