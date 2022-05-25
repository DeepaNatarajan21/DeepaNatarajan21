import pandas as pd 
df1=pd.read_csv('gl_ae.csv')
for i in df1['AECONTRT']:
    if i=='Yes':
        print(df1[['Subject', 'AETERM']])
shape=data1.shape
print(shape)
df1=pd.read_csv('gl_ae.csv')
ae=df1.columns.to_list()
print(ae)
df2=pd.read_csv('gl_cm.csv')
cm=df2.columns.to_list()
print(cm)
len(cm)
len(ae)
df2.columns.tolist()
df=pd.concat(map(pd.read_csv,['gl_cm.csv','gl_ae.csv']))
df.shape
for i in df['AECONTRT']:
    if i=='Yes':
        print(df[['Subject','CMINDC','AETERM']])
