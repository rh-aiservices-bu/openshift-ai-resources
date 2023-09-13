# OpenShiftAIOverview
And overview over OpenShift AI, containing technical content such as release-notes and demos.

## Release highlights (last 3)
### 1.32 - 04/09-2023
[Jira](https://issues.redhat.com/browse/RHODS-11794?jql=project%20%3D%20rhods%20AND%20%22Target%20Release%22%20%3D%20RHODS_1.32.0_GA) | [Official release documentation](https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science_self-managed/1.32/html/1.32_release_notes)

- 

### 1.31 - 14/08-2023
[Jira](https://issues.redhat.com/browse/RHODS-11371?jql=project%20%3D%20rhods%20AND%20%22Target%20Release%22%20%3D%20RHODS_1.31.0_GA) | [Official release documentation](https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science_self-managed/1.31/html/1.31_release_notes)

- 

### 1.30 - 24/07-2023
[Jira](https://issues.redhat.com/browse/RHODS-10191?jql=project%20%3D%20rhods%20AND%20%22Target%20Release%22%20%3D%20RHODS_1.30.0_GA) | [Official release documentation](https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science_self-managed/1.30/html/1.30_release_notes)

- 


## Demo resources

| Name    | Description | Updated |
| ------- | ----------- | ------- |
| Pipelines [[powerpoint]("https://docs.google.com/presentation/d/1K0MECjld3-ya5ii-nMy5cOorQ-bHw2gd9j7QpVmt_iY/edit#slide=id.g25869558928_0_79)] [[demo](https://github.com/RHRolun/pipelines_demo)] | Simple pipeline example that covers the basic functionality with Elyra and a slide deck that goes through the functionality. | July 12, 2023 |
| [Object detection workshop](https://github.com/mamurak/os-mlops/tree/main/notebooks/object-detection-example) | An end-to-end workshop that covers workbenches, serving, pipelines, and integrating in applications. | Aug 1, 2023 |
| [License plate workshop](https://github.com/rh-aiservices-bu/licence-plate-workshop) | ??? | Jun 28, 2023 |
| [Credit Card Fraud Detection with MLFlow](https://ai-on-openshift.io/demos/credit-card-fraud-detection-mlflow/credit-card-fraud/) | Shows how you can integrate MLFlow into your workflow using a simple credit card fraud detection usecase. | May 8, 2023 |
| [Financial Fraud Detection](https://ai-on-openshift.io/demos/financial-fraud-detection/financial-fraud-detection/) | The content in this repository describes how to use OpenShift Data Science to train and test a relatively simplistic fraud detection model, using RHODS workbench, S2I, Kafka, Grafana, | May 13, 2022 |
| Intelligent agriculture demo [[code](https://github.com/rh-aiservices-bu/intelligent-agriculture-demo)] [[deployment instructions](https://github.com/guimou/intelligent-agriculture-deployment)] [[workshop instructions](https://github.com/guimou/intelligent-agriculture-workshop/tree/main/documentation/modules/ROOT/pages)] | This demo aims at showcasing different technologies in an intelligent agriculture context: AI model training and serving for disease recognition in crops. 5G slices for two way communications between IoT/Field "devices". Edge computing at Telco location (MEC). Path optimization using Optapy and a PathFinding algorithm. Automated model updates. | May 9 2023 |

## Other
Roadmap: https://docs.google.com/presentation/d/1YKlaYhb8Du8clmEt3wMEWZ8F2dONp3Jbetpr2r47ego/edit#slide=id.g22b02b13193_13_0  
Self-managed documentation: https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science_self-managed/1-latest  
Managed documentation: https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science/1  
Learning material: https://docs.google.com/document/d/1oRDjbY2vEtPOAej01qlkMlhEa4CvozDRT8J6LURPmYo  





<table style="width:3500px">
<tr>
<th>Argument</th>
<th>Description</th>
</tr>
<tr>
<td>appDir</td>
<td>The top level directory that contains your app. If this option is used then
it assumed your scripts are in</td>
</tr>
<tr>
<td>baseUrl</td>
<td>By default, all modules are located relative to this path. If baseUrl is not
explicitly set, then all modules are loaded relative to the directory that holds
the build file. If appDir is set, then baseUrl should be specified as relative
to the appDir.</td>
</tr>
<tr>
<td>dir</td>
<td>The directory path to save the output. If not specified, then the path will
default to be a directory called "build" as a sibling to the build file. All
relative paths are relative to the build file.</td>
</tr>
<tr>
<td>modules</td>
<td>List the modules that will be optimized. All their immediate and deep
dependencies will be included in the module's file when the build is done. If
that module or any of its dependencies includes i18n bundles, only the root
bundles will be included unless the locale: section is set above.</td>
</tr>
</table>