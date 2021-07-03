# Colombian government public contracts analysis

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

The main source of data for this projec is the SECOP (versions 1 and 2). SECOP (Sistema Electrónico para la Contratación Pública) is a platform that contains information related to public expenses in Colombia. This information is publicly available and can be found at the webpage of the Ministry of Information and Communication. SECOP is segmented in two different versions depending on the information retrieval methodology of the platform: 

 - offline retrieval (SECOP 1) and online retrieval (SECOP 2).

SECOP 1 refers to a non automated platform for transaction process documentation. Most of the information from SECOP 1 comes from pdf files manually uploaded to the platform. On the other hand, SECOP 2 works as an online platform. The main advantage of SECOP 2 with respect to SECOP 1 is the information availability on a structured manner, instead of separated files with an unstandardized structure, SECOP 2 enables the information to the general public.
Each row in the SECOP dataset corresponds to a public process and the different columns allow to determine different characteristics for each of those process: 
 - textual description of the process
 - total cost
 - duration of the process
 - among other variables of interest. 
 - 
Those processes may or may not be related to a contract with the government and they may be finished or ongoing. The database is segmented depending on the public expenses platform utilized for data collection: 

 - SECOP 1 has 6.140.000 processes and SECOP 2 has 383.000 processes. 
 - Both sources of information contain, among others, the following variables of interest:
    - Textual description of the process. Important for latent economic sector identification of the processes based on text analysis.
    - Total cost of the process. Input variable for determining the amount invested for each economic sector mentioned in the contract.
    - Location of the process. Municipality where the process takes place.

Data is avaliable in the datos.gov.co goverment portal 

[Consolidated data](https://www.datos.gov.co/Gastos-Gubernamentales/SECOP-Integrado/rpmr-utcd)

![image](https://user-images.githubusercontent.com/33405407/124367544-f0a51100-dc0c-11eb-846a-e1fb7db5db0e.png)


# Web scraping tools for extended information
 


# Text analysis to identify general topics in the contract’s description using BETO (Spanish BERT Model) 
 
 
 
# Dash development for visualization and analysis (Dash + Python)
 
 
 
# OCR for information extraction from public contracts (Tesseract)
 
 
 
 # Graph analysis for contractors (NetworkX + Python)
