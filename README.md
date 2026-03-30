# DATA55500-Reproducibility
This project examines reproducibility in data science by attempting to replicate key results from the paper *"Macroeconomic Forecasting with Large Language Models"* using the FRED-MD dataset.

## References
- Paper: `https://arxiv.org/abs/2402.01801`
- Dataset (FRED-MD): `https://research.stlouisfed.org/econ/mccracken/fred-databases/`

## Objective
- Reproduce core forecasting methods from the paper  
- Compare baseline (AR) and multivariate (VAR) models  
- Evaluate performance using both static and rolling forecasts  
- Analyze reproducibility challenges and ethical implications  

## Methodology
- Dataset: FRED-MD (monthly macroeconomic variables)  
- Models: Autoregressive (AR) and Vector Autoregression (VAR)  
- Evaluation Metrics: RMSE and RMSFE  

## Key Results
- VAR outperformed AR under a static train-test split  
- AR outperformed VAR under rolling forecast evaluation  
- Results highlight the impact of evaluation methodology on model performance  

## Reproducibility
- Limited implementation details in the original paper required assumptions  
- A subset of variables was used due to computational constraints  
- Differences in preprocessing and setup led to variation in results  

## Ethical Considerations
- Reproducibility is essential for ensuring trust and reliability in research  
- Lack of transparency (e.g., missing code, unclear preprocessing, LLM training data) raises concerns about validity  

## Authors
- Tirth Laheri  
- Seth Phillips
- Sushmitha Sana
- Sudarshan Reddy
