# Credit_Fraud_Detection
Exploration into credit card fraud detection

TO add datasets run
X_train = pd.read_csv('https://github.com/limperstickhelp23/Credit_Fraud_Detection/blob/a4e466407b03d483be92a096bf9e6ecdf250dafb/preprocessing/X_train.csv?raw=True', index_col=0)
y_train = pd.read_csv('https://github.com/limperstickhelp23/Credit_Fraud_Detection/blob/a4e466407b03d483be92a096bf9e6ecdf250dafb/preprocessing/y_train.csv?raw=True', index_col=0 )
X_test = pd.read_csv('https://github.com/limperstickhelp23/Credit_Fraud_Detection/blob/a4e466407b03d483be92a096bf9e6ecdf250dafb/preprocessing/X_test.csv?raw=True', index_col=0)
#y_train.drop(['Unnamed: 0'], axis=1, inplace=True)
y_test = pd.read_csv('https://github.com/limperstickhelp23/Credit_Fraud_Detection/blob/a4e466407b03d483be92a096bf9e6ecdf250dafb/preprocessing/y_test.csv?raw=True', index_col=0)
