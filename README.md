## The Issue:
The final goal of this script is a camparison between two data dictionaries. Both data dictionaries are in google sheets. One of them is a simple sheet but the other one contains multiple sheets and needs to be integrated in one dataframe.
## Steps:
1- Connect throught Google API with its token (you need to have access for the sheet)<br>
2- Create dataframe of first data dictionary<br>
3- Connect throught Google API with its token (you need to have access for the sheets)<br>
4- Exclude extra tabes <br>
5- Integrate all sheets into one dataframe --> second data dictionary<br>
6- Compare two dataframes in pandas and insert them into S3 <br>
7- From s3 into AWS Redshift<br>
## Challenge
For connecting two dataframes we need a name convertor. This convertor in one way and change naming from Salesforce format to Fivetran format.
