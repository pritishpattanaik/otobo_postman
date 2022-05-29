# What is OTOBO?

######  OTOBO is an extremely flexible, web-based open-source ticketing tool, used to streamline communication in service organisations such as IT Help-desks, Customer Service, Call Centres etc. It provides classical ticketing functionality, a knowledge base/FAQs with internal and external interface, helps to automate processes and can be extended by an ITSM component with a CMDB to keep track of IT components – or buildings, office plants, cars etc. OTOBO is a fork based on ((OTRS)) Community Edition, started in 2019 to go back to the roots and offer a 100 % free tool, rooted in a strong community, and backed up by professional business services.


# OTOBO Postman Collection API example request

- **Get Ticket**

- **Create Ticket**
 
- **Get SessionID**

- **Search Ticket**


# import postman schema OTOBO-OTRS-API.postman_collection.json to your postman 

##### Please set otobo_url, mywebservice, otobo_user and otobo_pw after you import jason file


**OTOBOGetToken**

```
{{otobo_url}}/otobo/nph-genericinterface.pl/Webservice/{{mywebservice}}/Session/GetToken?UserLogin={{otobo_user}}&Password={{otobo_pw}}
```

##### Once you sucessfully imported this collection to your postman software, you can generate code in most programming language. 


## How to create web service as a provider in OTOBO/OTRS system using OTOBO manual

OTOBO online manual for your reference (https://doc.otobo.org/manual/admin/10.1/en/content/processes-automation/web-services.html)

## You can directly import example web serices YML file given here. 

##### Login to OTOBO - admin - Webservice Management - Add Web Services -  Import Web Services. 







