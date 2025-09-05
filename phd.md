# PhD Research: Machine Learning for Arterial Pressure Pulse Analysis

## Research Overview
My 2006 PhD thesis at UNSW investigated the application of advanced machine learning techniques to arterial pressure wave analysis. The research established the theoretical foundation for non-invasive blood pressure estimation using arterial wave morphology, with significant implications for cardiovascular diagnostics.

## Research Objectives

### Primary Goal
Determine the theoretical feasibility of using arterial wave shape to estimate absolute arterial blood pressure with clinical-grade accuracy, potentially enabling non-invasive alternatives to invasive catheter sensors.

### Secondary Goal
Analyze and improve the accuracy of parameters estimated by the SphygmoCor® device, a commercial system for arterial pulse wave analysis.

## Technical Approach

### Unsupervised Learning Methods
- **Self-Organizing Maps (SOMs)**: Applied to identify natural patterns and relationships in arterial pressure wave shapes
- **Independent Component Analysis (ICA)**: Used to separate true pressure signals from noise components and artifacts
- **Clustering Techniques**: Employed to categorize wave shapes by morphological characteristics

### Supervised Learning Methods
- **Multivariate Linear Regression**: Applied to basic parameter estimation
- **Stepwise Regression**: Used for feature selection and parameter optimization
- **Principal Component Regression**: Implemented for robust pressure estimation
- **Treenet®**: Employed for non-linear relationship modeling
- **Cross-Validation Techniques**: Applied to validate predictive accuracy

## Key Findings

### Pattern Recognition
- Confirmed that observed arterial pressures affect wave shape in patterns consistent with theoretical hemodynamic models
- Demonstrated that SOMs effectively visualize complex relationships between wave characteristics and physiological parameters

### Regression Model Performance
- Developed models that reproduced SphygmoCor® parameters with high accuracy
- Created more robust algorithms than the device's proprietary software for certain parameters
- Established that principal component regression could estimate continuous peripheral and central pressures from wave shape

### Clinical Implications
- Demonstrated theoretical feasibility of estimating blood pressure from wave morphology within accuracy limits set by the Association for the Advancement of Medical Instrumentation (AAMI)
- Identified new potential roles for non-invasive sphygmographic devices beyond feature estimation
- Established a foundation for continuous, non-invasive blood pressure measurement techniques

## Technical Skills Applied
- Advanced statistical analysis
- Machine learning algorithm development
- Signal processing
- Medical data interpretation
- Physiological modeling

## Research Impact
This research established the mathematical framework for non-invasive blood pressure estimation using machine learning techniques, potentially enabling continuous monitoring without invasive procedures. The methodologies developed have applications beyond cardiovascular measurements to other physiological signal analysis domains.
