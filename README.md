# workshop-agenda

## Agenda

Time | Session
---- | -------
8:30 AM - 8:45 AM   | _Introductions & Kickoff_ [Brandon - Cerner]
8:45 AM - 9:00 AM   | _Session 0: API Lifecycle Management_ [Nuwan - WSO2](https://docs.google.com/presentation/d/1R_HXtXGPwvIMQc-3kFJmmf_tsZMr1Li4LWVDVdkv4wQ/edit?usp=sharing)
9:00 AM - 9:15 AM   | _Session 1: Prototype the API_ [Nuwan - WSO2](https://docs.google.com/presentation/d/1R_HXtXGPwvIMQc-3kFJmmf_tsZMr1Li4LWVDVdkv4wQ/edit?usp=sharing)
9:15 AM - 9:30 AM   | _Session 2: [Creating Services on PCF](https://github.com/cts-workshop-12-2018/creating-services)_ [Febin - Cerner]
9:30 AM - 9:45 AM   | _Session 3: [Deploy a web app to PCF](https://github.com/cts-workshop-12-2018/angular7-m0)_ [DaShaun - Pivotal]
9:45 AM - 10:00 AM  | _Break - Order Lunch_
10:00 AM - 10:30 AM | _Session 4: Creating a new [Java](https://github.com/cts-workshop-12-2018/spring-employee-service-m1) or [DotNet](https://github.com/cts-workshop-12-2018/dotnet-employee-service-m1) App - Starting from zero_ [DaShaun - Pivotal]
10:30 AM - 11:30 AM | _Session 5: CRUD with [Java w/ Spring Data JPA](https://github.com/cts-workshop-12-2018/spring-employee-service-m2) or [DotNet w/ Entity Framework](https://github.com/cts-workshop-12-2018/dotnet-employee-service-m2)_ [Robert - Magenic]
11:30 AM - 12:00 PM | _Session 6: Add Discovery and Configuration_ [DaShaun - Pivotal]
12:00 PM - 1:00 PM  | _Working Lunch - Hands On Help - Q&A_
1:00 PM - 1:45 PM   | _Session 7: Publishing and Consuming_ [Manoj - WSO2]
1:45 PM - 3:45 PM   | _Session 8: Adding Oauth2_
3:45 PM - 4:00 PM   | _Break_
4:00 PM - 4:30 PM   | _Wrap-up, Q&A, Course evaluation_

# Pre Requisites

## CF CLI (2 mins)

Download and install CF CLI from the below link

https://docs.run.pivotal.io/cf-cli/install-go-cli.html

## Tools

### JDK (Only those who like to develop in Java) (5 mins)

Download and install [Java JDK](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

To set __JAVA_HOME__, do the following:

* Right click My Computer and select Properties

* On the Advanced tab, select Environment Variables, and then edit __JAVA_HOME__ to point to where the JDK software is located, for example, C:\Program Files\Java\jdk1.6.0_02.

### IDE (5 - 10 mins)

An IDE of your choice, preferably [Spring Tool Suite](https://spring.io/tools) (for Java) and  [Visual Studio](https://visualstudio.microsoft.com/downloads/) (for .Net)

### Git (3 mins)

Download and install [Git](https://git-scm.com/downloads)


## Verify Access

Login to the PAS foundation's web portal (e.g. https://apps.sys.prod.us-west-2.cernercf.io/).

Verify that you are able to see `enterprise-services-poc` Org and a space named with your Corporate ID
