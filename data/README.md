The API Stack
=========

I am the API Evangelist, and this is my API Stack. Here you will find all of the companies, organizations, and government agencies I track on as part of my API monitoring. My goal is to not just have a directory of APIs, but a machine readable index of the best APIs out there. 

With the API Stack, I am focusing on generating APIs.json indexes of APIs that are defined using Swagger and API Blueprint. You can access a single APIs.json for this site (http://theapistack.com/apis.json), and then spider a list of APIs.json entries for each company, which will then give you links to each API, any supporting Swagger, API Blueprint, and other building blocks of each API's operations. You can find all API definitions under /data folder - https://github.com/api-stack/api-stack/tree/gh-pages/data.

One important question out there is: What is a complete APIs.json, Swagger or API Blueprint? We are working on a potential definition for this, which you can follow the evolution, here on the API Stack research site--currently we have (thanks to APIMATIC):

* Valid JSON
* BaseURIs
* Authentication Information
* Endpoint OperationIds/NickNames
* Schemas/Models
* Error Codes/Messages

The goal is to be working to evolve this definition, and establish services and tooling to help validate and certify APIs.json, Swagger, and API Blueprint files. All work is conducted via this Github repository, with the conversation around work conducted for each company, possessing its own Github Issue. All other support for this project will be done through the project's Github issues, and regular Github workflow.

If you want to get involved as a partner, let me know. We need as many people contributing to, and working from a common set of complete API definitions, that represent the entire API ecosystem--then we'll start seeing some benefits emerge that help strengthen the entire API economy.
