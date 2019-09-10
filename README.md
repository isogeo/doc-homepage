# Isogeo documentations homepage

[![Build Status](https://dev.azure.com/isogeo/Documentations/_apis/build/status/isogeo.doc-homepage?branchName=master)](https://dev.azure.com/isogeo/Documentations/_build/latest?definitionId=35&branchName=master)

A single and simple HTML page listing Isogeo online documentations ([see Github repositories](https://github.com/search?q=topic%3Adocumentation+org%3Aisogeo&type=Repositories)).

## Deployment

It's deployed on Isogeo Azure (Storage v2 Static website) using Azure DevOps ([see config](https://github.com/isogeo/doc-homepage/blob/master/azure-pipelines.yml)):

* QA: <https://qaisogeohelp.z28.web.core.windows.net/>
* PROD: <https://prodisogeohelp.z28.web.core.windows.net/>

Deployment rules:

* each commit triggers a deployment on QA
* each tagged commit triggers a deployment on PROD - [see tags](https://github.com/isogeo/doc-homepage/tags)
