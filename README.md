The API Stack
=========

I am the API Evangelist, and this is my API Stack. Here you will find all of the companies, organizations, and government agencies I track on as part of my API monitoring. My goal is to not just have a directory of APIs, but a machine readable index of the best APIs out there. 

With the API Stack, I am focusing on generating APIs.json indexes of APIs that are defined using Swagger and API Blueprint. You can access a single APIs.json for this site, and then spider a list of APIs.json entries for each company, which will then give you links to each API, any supporting Swagger, API Blueprint, and other building blocks of each API's operations.

You can browse this site by business sector (loose tags), or see a complete list of companies, and their APIs. Each company present has a folder in the gh-pages branch data folder, and each company has an APIs.json, Swagger, or potentially API Blueprint file (coming soon). If there is a company missing, that you think should be in the stack, submit a pull request and add to the folder, and master APIs.json. If there is a Swagger file, or API Blueprint file that is incomplete or missing, submit a pull request with the changes you want to see.

I encourage you to fork this work, and contribute back. I am currently working with three partners to make it as complete as possible:

* 3Scale
* APIs.io
* APIMATIC
* SDKs.io
* Blockspring
* 
We want to make sure the best APIs out there are represented, and have complete APIs.json files for each company, along with complete Swagger and API Blueprint specifications for the best public APIs out there.  

One important question out there is: What is a complete APIs.json, Swagger or API Blueprint? We are working on a potential definition for this, which you can follow the evolution, here on the API Stack research site--currently we have (thanks to APIMATIC):

* Valid JSON
* BaseURIs
* Authentication Information
* Endpoint OperationIds/NickNames
* Schemas/Models
* Error Codes/Messages
* 
We will be working to evolve this definition, and establish services and tooling to help validate and certify APIs.json, Swagger, and API Blueprint files. All work is conducted via this Github repository, with the conversation around work conducted for each company, possessing its own Github Issue. All other support for this project will be done through the project's Github issues, and regular Github workflow.

If you want to get involved as a partner, let me know. We need as many people contributing to, and working from a common set of complete API definitions, that represent the entire API ecosystem--then we'll start seeing some benefits emerge that help strengthen the entire API economy.
