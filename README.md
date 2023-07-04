[![Generic badge](https://img.shields.io/badge/status-work--in--progress-important.svg)](https://shields.io/) 

***

:warning: **This is not an official Google product.**<BR>This implementation is not an official Google product, nor is it part of an official Google product. Support is available on a best-effort basis via GitHub.

***

<BR>

## Welcome to the apigee-cicd wiki! 

This wiki contains links to sample Apigee CI/CD implementations and tools, for [Apigee Edge/OPDK](https://docs.apigee.com/), [Apigee X/hybrid](https://cloud.google.com/apigee/docs/) + Apigee [Integration](https://cloud.google.com/apigee/docs/api-platform/integration/what-is-apigee-integration) & [Connectors](https://cloud.google.com/apigee/docs/api-platform/connectors/about-connectors).

<BR>



##  Apigee 

Simple Apigee proxy deployment using main pipeline solutions:

||  Pipeline |  API Proxy & Config. |  Integration (1)|  API Hub (2) | 
|---|---|---|---|---|
|<img src="https://cdn.iconscout.com/icon/free/png-256/azure-devops-3628645-3029870.png" width="30"> |  Azure Pipeline | [Sample](https://github.com/echarish/apigee-cicd/tree/main/Apigee-ApiHub-Simple-Azure-Pipeline) | - | [Sample](https://github.com/echarish/apigee-cicd/tree/main/Apigee-ApiHub-Simple-Azure-Pipeline) |
|<img src="https://a.slack-edge.com/80588/img/plugins/circleci/service_512.png" width="30"> |  CircleCI |  [Sample](https://github.com/echarish/apigee-cicd/tree/main/Apigee-Simple-CircleCI-Pipeline) |  - | - |
|<img src="https://raw.githubusercontent.com/phylus-alpha/phylus/master/images/github.png" width="30"> |  GitHub | [Sample](https://github.com/echarish/apigee-cicd/tree/main/Apigee-Simple-Github-Pipeline)  | [Sample](https://github.com/echarish/apigee-cicd/tree/main/Apigee-Integration-Simple-GitHub-Pipeline) | [Sample](https://github.com/echarish/apigee-cicd/tree/main/Apigee-ApiHub-Simple-Github-Pipeline) |
| <img src="https://about.gitlab.com/images/logo.png" width="30"> |  GitLab | [GitLab Sample](https://gitlab.com/clalevee/apigee-simple-gitlab_ci-pipeline-v2)  | - |  [GitLab Sample](https://gitlab.com/clalevee/apigee-apihub-simple-gitlab-pipeline)  |
|<img src="https://avatars.githubusercontent.com/u/38220399?s=200&v=4" width="30"> |  Google Cloud Build | [Apigee DevRel GitHub](https://github.com/apigee/devrel/tree/main/references/cicd-pipeline)    |  - | - |
|<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e9/Jenkins_logo.svg/1200px-Jenkins_logo.svg.png" width="30"> |  Jenkins | [Apigee DevRel GitHub](https://github.com/apigee/devrel/tree/main/references/cicd-pipeline)  | - | - |


(1) End to end deployment and testing of an [Apigee Connector](https://cloud.google.com/apigee/docs/api-platform/connectors/about-connectors) (Google BigQuery), an [Apigee Integration](https://cloud.google.com/apigee/docs/api-platform/integration/what-is-apigee-integration) workflow and an Apigee Proxy.

(2) API SDLC ("design-first" approach) illustration relying on [Apigee API hub](https://cloud.google.com/apigee/docs/api-hub/what-is-api-hub) and Apigee X/hybrid 
<BR>

##  Apigee Complementary tools
 

|  Tool |  Link | Description | 
|---|---|---|
|  CICD Pipeline for SharedFlows | [Apigee DevRel GitHub](https://github.com/apigee/devrel/tree/main/references/cicd-sharedflow-pipeline) <img src="https://github.com/echarish/apigee-cicd/tree/main/apigee-cicd/blob/main/apigee-logo.jpg?raw=true" alt="logo" width="20"/>  |  CI/CD pipeline for Apigee sharedflow using the Apigee Deploy Maven Plugin |
|  Apigee X Environment Selector | [Sample](https://github.com/echarish/apigee-cicd/tree/main/apigee-envselector) | Select CI/CD pipeline target environment from an Environment Group |

<BR>

## Apigee Integration (and Apigee Connectors)
 

|  Tool |  Link | Description |
|---|---|---|
|  Apigee acidt | [Sample](https://github.com/echarish/apigee-cicd/tree/main/apigee-acidt) | Apigee Connection and Integration Deployment Tool |


