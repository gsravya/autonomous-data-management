# Autonomous Data Management
Oct 11, 2018

## Introduction
This workshop will walk you through the different modules that achieve a use case of solving data integration and data management challenges typically present in an organization. Managing the data flow and integrating the data from many varied kinds of data sources pose a serious challenge to any organization. This effective management of the data is very critical as it can help derive better business insights that can drive business growth and development. 

In this workshop, we are going to integrate data from different data sources, especially big data and relational data in one place - Oracle Autonomous Data Warehouse Cloud - using Oracle cloud products and services. To try Oracle Cloud services and to sign up for a free trial account, please follow the steps outlined in the following sections of this lab.

Oracle Autonomous Data Warehouse Cloud (ADWC) provides an easy-to-use, fully autonomous database that scales elastically, delivers fast query performance and requires no database administration.


## Goals
* Get comfortable with Oracle public cloud services
* Provision a new ADWC service
* Provision other Oracle Cloud services as needed
* Integrate relational data into ADWC using Oracle Data Integration Platform Cloud service (DIPC) from an Oracle database
* Integrate big data into ADWC using Oracle Data Lake
* Create an external table from a file in Oracle Cloud Infrastructure (OCI) Object Storage in ADWC
* Use Oracle Analytics Cloud (OAC) to run reports on the consolidated data in ADWC

## To Learn More About ADWC
* [Oracle ADWC website](https://www.oracle.com/database/data-warehouse.html)
* [Oracle ADWC ipaper](http://www.oracle.com/us/products/database/autonomous-dw-cloud-ipaper-3938921.pdf)
* [Oracle ADWC Documentation](https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/index.html)


# Workshop Details
## How to access the workshop
* Please go to [Github Pages URL](https://cloudsolutionhubs.github.io/Autonomous-Data-Management) to follow the hands-on workshop.

## Acquire an Oracle Cloud Trial or Workshop Account

- Bookmark this page for future reference.

- Please click on the following link to create your <a class=“trial-link” href="https://myservices.us.oraclecloud.com/mycloud/signup?language=en&sourceType=:ex:tb:::RC_NAMK181011P00041:ATPHOL&SC=:ex:tb:::RC_NAMK181011P00041:ATPHOL&pcode=NAMK181011P00041" target="_trial">Free Account</a>, and complete all the required steps to get your free Oracle Cloud Trial Account. When you complete the registration process you'll receive a credit that will enable you to complete the lab for free.  Additionally, you'll have 1000s of hours left over to continue to explore the Oracle Cloud.

  - Soon after requesting your trial you will receive the following email. You may begin working on the [Introduction-Start-Here.md](Introduction-Start-Here.md) lab.

  ![](images/code_9.png)


## Oracle Cloud Services Used
* [Oracle Autonomous Data Warehouse Cloud Service (ADWC)](https://cloud.oracle.com/en_US/datawarehouse)
* [Oracle Database Cloud Service (DBCS)](https://cloud.oracle.com/database)
* [Oracle Data Integration Platform Cloud (DIPC)](https://cloud.oracle.com/en_US/data-integration-platform)
* [Oracle Big Data Cloud (BDC)](https://cloud.oracle.com/bigdata)
* [Oracle Cloud Infrastructure Object Storage](https://cloud.oracle.com/storage/object-storage/features)
* [Oracle Analytics Cloud (OAC)](https://cloud.oracle.com/en_US/oac)


## Lab 050: Introduction - Start Here
**Documentation**: [Lab050-Introduction-Start-Here.md](Lab050-Introduction-Start-Here.md)

**Objectives**:

* Introduction to the use case of the entire workshop
* Acquire an Oracle Cloud Account
* Learn how to sign-in to the Oracle Public Cloud
* Learn how to provision a new ADWC database
* Learn how to download the client credentials wallet file
* Learn how to connect to ADWC from Oracle SQL Developer


## Lab 100: Integrate Relational Data into ADWC
**Documentation**: [Lab100-IntegrateRelationalDataIntoADWC.md](Lab100-IntegrateRelationalDataIntoADWC.md)

**Objectives**:

* Provision an Oracle Database Cloud Service (DBCS) instance
* Connect to the DBCS instance using SQL Developer and import relational data as a table
* Create empty table in ADWC with same structure as that in DBCS
* Provision an Oracle Data Integration Platform Cloud (DIPC) instance
* Configure DIPC to support ADWC as the target and the DBCS as the source
* Use Oracle Data Integrator Studio (ODI Studio) which is part of DIPC to load data from DBCS to ADWC
* Verify if the data is loaded in ADWC


## Lab 200: Integrate Big Data into ADWC
**Documentation**: [Lab200-IntegrateBigDataIntoADWC.md](Lab200-IntegrateBigDataIntoADWC.md)

**Objectives**:

* Provision an Oracle Big Data Cloud (BDC) instance
* Upload data into HDFS of the BDC cluster node
* Create an Object Storage bucket in Oracle Cloud Infrastructure (OCI)
* Process and store the data from BDC HDFS to OCI Object Storage bucket
* Create an empty table in ADWC
* Load processed big data file from OCI Object Storage to Oracle ADWC
* Verify if the data is loaded in ADWC


## Lab 300: Create External Table in ADWC
**Documentation**: [Lab300-CreateExternalTableInADWC.md](Lab300-CreateExternalTableInADWC.md)

**Objectives**:

* Upload data file to the OCI Object Storage
* Create an external table in ADWC
* Run a sample query to verify if the external table is created in ADWC


## Lab 400: Visualization using Oracle Analytics Cloud (OAC)
**Documentation**: [Lab400-VisualizationUsingOAC.md](Lab400-VisualizationUsingOAC.md)

**Objectives**:

* Create a sample consolidated view on all the tables in ADWC
* Use OAC to visualize and analyze the report

