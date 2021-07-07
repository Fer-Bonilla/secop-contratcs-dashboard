# Colombian government public contracts analysis (Under construction)

This is project to build an advanced tool to analyze the goverment public contracts information from the SECOP 2 procurement platform from the Colombias goverment. The work include this task

 - Public databases used from datos.gov.co Colombian portal.
 - Web scraping tools for extended information
 - Text analysis to identify general topics in the contract’s description using BETO (Spanish BERT Model) 
 - Dash development for visualization and analysis (Dash + Python)
 - OCR for information extraction from public contracts (Tesseract)
 - Graph analysis for contractors (NetworkX + Python)

# Project description

With this project I explore the analysis of the public government biding process, using public databases and web scraping tools to gather information and consolidate a data repository to provide some advanced analytics like graph analysis, text analytics, and some patterns referred about how government agencies expense the tax money from the citizens. This project is intended to be public and open source and organizations and companies can use all the components and developments under the MIT license terms.

# Public databases used from datosbiertos.gov.co Colombian portal

The main source of data for this projec is the SECOP (versions 1 and 2). SECOP (Sistema Electrónico para la Contratación Pública) is a platform that contains information related to public expenses in Colombia. This information is publicly available and can be found at datos.gov.co , the open data goverment portal.

SECOP 1 refers to a non automated platform for transaction process documentation. Most of the information from SECOP 1 comes from pdf files manually uploaded to the platform. On the other hand, SECOP 2 works as an online platform. The main advantage of SECOP 2 with respect to SECOP 1 is the information availability on a structured manner, instead of separated files with an unstandardized structure, SECOP 2 enables the information to the general public.

You can explore the SECOP platform in the website [Portal Colombia compra](https://colombiacompra.gov.co/)

Those processes may or may not be related to a contract with the government and they may be finished or ongoing. The database is segmented depending on the public expenses platform utilized for data collection. You can donwload the data drom SECOP1 or SECOP2 or the consolidated info from datos.gov.co goverment portal [Consolidated data](https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-Integrado/rpmr-utcd)


# Exploratory data analysis

There are some exploration to do:

###  Data in the SECOP1 dataset

Data source: [https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-I/xvdy-vvsk](https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-I/xvdy-vvsk)

![image](https://user-images.githubusercontent.com/33405407/124547521-20a50d80-dde1-11eb-8602-7e1bfcde45f2.png)

###  Data in the SECOP2 dataset

Data source: [https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-II-Procesos-de-Contrataci-n/p6dx-8zbt](https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-II-Procesos-de-Contrataci-n/p6dx-8zbt)

![image](https://user-images.githubusercontent.com/33405407/124547727-6d88e400-dde1-11eb-8ca2-03c2289c7cdf.png)


###  Data in the consolidated dataset

Data source: [https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-Integrado/rpmr-utcd](https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-Integrado/rpmr-utcd)

![image](https://user-images.githubusercontent.com/33405407/124546293-40d3cd00-dddf-11eb-8beb-bb8c000d9f62.png)


###  Data in the SECOP webpage

![image](https://user-images.githubusercontent.com/33405407/124548260-54346780-dde2-11eb-8be4-8967b6b24fde.png)

Site link. [https://colombiacompra.gov.co/secop-ii](https://colombiacompra.gov.co/secop-ii)


The EDA notebook for the process is on: [link to EDA notebook](https://github.com/Fer-Bonilla/secop-contratcs-dashboard/blob/main/dataset_summary.ipynb)


# Web scraping tools for extended information
 


# Text analysis to identify general topics in the contract’s description using BETO (Spanish BERT Model) 
 
 
 
# Dash development for visualization and analysis (Dash + Python)
 
 
 
# OCR for information extraction from public contracts (Tesseract)
 
 
 
 # Graph analysis for contractors (NetworkX + Python)
