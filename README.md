 # LRMAHpan
LRMAHPan: a novel tool for multi-allelic HLA presentation prediction using Resnet-based and LSTM-based neural networks

## INSTALL<br>
#### install pytorch gpu<br>
#### install torchtext<br>
#### install spacy<br>
#### install pandas<br>
#### install numpy<br>
  
## DATA  
Big data for training and 10 independent test datasets are stored in the ***data.zip*** under github's master path: https://github.com/Luckysoutheast/LRMAHpan/tree/master. You can learn more about the details of the original data in this link.

## USE<br>
#### python predict_res.py –t  testfile.csv –o outfile.csv  

Test set should be a comma-separated CSV files. The files should have the following columns (with headers):
peptide, label, A1, A2, B1, B2, C1, C2(the label column is not required when you predict)  
  
### For example:  
#### python predict_res.py -t ./uploaded/multiple_query.csv -o result_multiple_query.csv  

## Result
The results of the stand-alone test set are stored in the ***test_result.zip*** file
