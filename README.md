Datasets used for the paper: 

> Attachment relationships, identity and well-being in seminarians (2022)
> 
> De Gregorio A., Della Giulia A., Vistocco D.
> 
> submited to: _Journal of Heath and Psychology_, Springer
> 

The repository contains three files in MS-Excel format:

- **model_data.xlsx**: a table with 159 rows (seminarians) and 118 columns (indicators)

- **model_data_no_na.xlsx**: the same table above described where missing value were imputed fitting a low-rank matrix approximation to a matrix with missing values via nuclear-norm regularization. For details, see:

Rahul Mazumder, Trevor Hastie and Rob Tibshirani (2010)
Spectral Regularization Algorithms for Learning Large Incomplete Matrices, https://web.stanford.edu/~hastie/Papers/mazumder10a.pdf
Journal of Machine Learning Research 11 (2010) 2287-2322
    
- personal_info.xlsx: dataset with demographic information (to fill, ...). Data contains 159 rows (seminarians) and ? columns (...)
