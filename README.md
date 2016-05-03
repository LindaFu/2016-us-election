# 2016-us-election

2016 US Election Demographic analysis -

Identify voter patterns - if vote candicates based on the following demographic features:

- race
- medium income
- college education
- population density

Goals :
 - Identify the corelation among these features
 - show which candidate do better in certain categories (such counties with more higher education voters) 
 - predict if certain features change (up or down), which candicate will perform better 

data set :
https://www.kaggle.com/benhamner/2016-us-election
-> click download

(1) primary_results.csv

state,state_abbreviation,county,fips,party,candidate,votes,fraction_vote

(2) county_facts.csv

fips,area_name,state_abbreviation,PST045214,PST040210,PST120214,POP010210,AGE135214,AGE295214,AGE775214,SEX255214,RHI125214,RHI225214,RHI325214,RHI425214,RHI525214,RHI625214,RHI725214,RHI825214,POP715213,POP645213,POP815213,EDU635213,EDU685213,VET605213,LFE305213,HSG010214,HSG445213,HSG096213,HSG495213,HSD410213,HSD310213,INC910213,INC110213,PVY020213,BZA010213,BZA110213,BZA115213,NES010213,SBO001207,SBO315207,SBO115207,SBO215207,SBO515207,SBO415207,SBO015207,MAN450207,WTN220207,RTN130207,RTN131207,AFN120207,BPS030214,LND110210,POP06021

(3) county_facts_datadictionary.csv

column_name,description
