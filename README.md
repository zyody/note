# note

在服务器上安装python，setuptools, pip。  

1. python  

proxychains wget https://www.python.org/ftp/python/2.7.13/Python-2.7.13.tgz  
tar -zxvf Python-2.7.13.tgz  
cd Python-2.7.13/  
./configure  
make  
mv ./python ./python27  
pwd  
vim ~/.bash_profile  
source ~/.bash_profile  
ls Lib/site-packages/  

2. setuptools  
proxychains wget https://files.pythonhosted.org/packages/1a/04/d6f1159feaccdfc508517dba1929eb93a2854de729fa68da9d5c6b48fa00/setuptools-39.2.0.zip  
unzip setuptools-39.2.0.zip  
cd setuptools-39.2.0/  
proxychains python27 setup.py install --user  

3. pip  
proxychains wget https://files.pythonhosted.org/packages/ae/e8/2340d46ecadb1692a1e455f13f75e596d4eab3d11a57446f08259dee8f02/pip-10.0.1.tar.gz  
tar -zxvf pip-10.0.1.tar.gz  
cd pip-10.0.1/  
python27 setup.py install --user  
