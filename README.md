# OpenShift AI Resources
Easy access to technical OpenShift AI resources, such as demos and release-notes.

## Demo resources

<table>
<tr>
<th>Name</th>
<th>Description</th>
<th>Updated</th>
</tr>
<tr>
<td>Workshop: Object Detection with Pipelines</br>[<a href="https://codrinbucur.github.io/rhods-od-workshop/rhods-od-workshop/index.html">workshop instructions</a>][<a href="https://github.com/mamurak/os-mlops/blob/main/rhods-od-workshop-instructions.md">deployment instructions</a>]</td>
<td>An end-to-end workshop that covers workbenches, serving, pipelines, and integrating in applications.</td>
<td>Aug 1, 2023</td>
</tr>
<tr>
<td><a href="https://redhat-scholars.github.io/rhods-od-workshop/rhods-od-workshop/index.html">Workshop: Object Detection with Kafka</a></td>
<td>In this workshop, you’ll learn an easy way to incorporate data science and AI/ML into an OpenShift development workflow. </td>
<td>Aug 6, 2023</td>
</tr>
<tr>
<td><a href="https://github.com/rh-aiservices-bu/licence-plate-workshop">Workshop: License plates</a></td>
<td>In this introductory workshop, you’ll learn how to use Red Hat OpenShift Data Science to recognize licence plates in car pictures, and extract the number from this plate.</td>
<td>Jun 28, 2023</td>
</tr>
<tr>
<td>WorkShop and Demo: Intelligent agriculture </br>[<a href="https://github.com/rh-aiservices-bu/intelligent-agriculture-demo">demo</a>][<a href="https://github.com/guimou/intelligent-agriculture-deployment">deployment instructions</a>][<a href="https://github.com/guimou/intelligent-agriculture-workshop/tree/main/documentation/modules/ROOT/pages">workshop instructions</a>]</td>
<td>This demo aims at showcasing different technologies in an intelligent agriculture context:  
<ul> 
    <li>AI model training and serving for disease recognition in crops.</li>
    <li>5G slices for two way communications between IoT/Field "devices".</li>
    <li>Edge computing at Telco location (MEC).</li>
    <li>Path optimization using Optapy and a PathFinding algorithm.</li>
    <li>Automated model updates.</li>
</ul>
</td>
<td>May 9 2023</td>
</tr>
<tr>
<td><a href="https://github.com/eartvit/xraylab-demo">Demo: X-Ray Lab</a></td>
<td>Showcase of an intelligent application for pneumonia risk detection using Machine Learning model workloads on Red Hat OpenShift.</td>
<td>Aug 15, 2023</td>
</tr>
<tr>
<td><a href="https://ai-on-openshift.io/demos/telecom-customer-churn-airflow/telecom-customer-churn-airflow/">Demo: Telecom Customer Churn using Airflow</a></td>
<td>This demo is demonstrates how Red Hat OpenShift Data Science (RHODS) and Airflow can be used together to build an easy-to-manage pipeline.</td>
<td>Feb 22, 2023</td>
</tr>
<tr>
<td><a href="https://ai-on-openshift.io/demos/credit-card-fraud-detection-mlflow/credit-card-fraud/">Demo: Credit Card Fraud Detection with MLFlow</a></td>
<td>Shows how you can integrate MLFlow into your workflow using a simple credit card fraud detection usecase.</td>
<td>May 8, 2023</td>
</tr>
<tr>
<td><a href="https://ai-on-openshift.io/demos/financial-fraud-detection/financial-fraud-detection/">Demo: Financial Fraud Detection</td>
<td>The content in this repository describes how to use OpenShift Data Science to train and test a relatively simplistic fraud detection model, using RHODS workbench, S2I, Kafka, and Grafana.</td>
<td>May 13, 2022</td>
</tr>
<tr>
<td><a href="https://ai-on-openshift.io/demos/yolov5-training-serving/yolov5-training-serving/">Demo: YoloV5 Training and Serving</td>
<td>In this tutorial, we're going to see how you can customize YOLOv5, an object detection model, to recognize specific objects in pictures, and how to deploy and use this model.</td>
<td>July 3, 2023</td>
</tr>
<tr>
<td><a href="https://ai-on-openshift.io/demos/water-pump-failure-prediction/water-pump-failure-prediction/">Demo: Water Pump Failure Prediction</td>
<td>This demo shows how to do detection of anomalies in sensor data. This web app allows you to broadcast various sources of data in real time.</td>
<td>May 6, 2023</td>
</tr>
<tr>
<td><a href="https://ai-on-openshift.io/demos/smart-city/smart-city/">Demo: Smart City, an Edge-to-Core Data Story</td>
<td>In this demo, we show how to implement this scenario:
<ul>
    <li>Using a trained ML model, licence plates are recognized at toll location.</li>
    <li>Data (plate number, location, timestamp) is send from toll locations (edge) to the core using Kafka mirroring to handle communication issues and recovery.</li>
    <li>Incoming data is screened real-time to trigger alerts for wanted vehicles (Amber Alert).</li>
    <li>Data is aggregated and stored into object storage.</li>
    <li>A central database contains other information coming from licence registry system: car model, color,…​</li>
    <li>Data analysis leveraging Presto and Superset is done against stored data.</li>
</ul>
</td>
<td>Jun 16, 2023</td>
</tr>
<tr>
<td><a href="https://github.com/rh-aiservices-bu/llm-on-openshift">LLM deployment and application examples</a></td>
<td>Describes how to deploy TGIS Serving, build a RAG, and more.</td>
<td>Oct 4, 2023</td>
</tr>
<tr>
<td><a href="https://github.com/sa-mw-dach/windy-journey/tree/main">Workshop: Windturbine damage detection</td>
<td>This repository serves as the foundation for the Windy Journey workshop</br>Note: GPU is advised to run it.</td>
<td>Nov 28, 2023</td>
</tr>
<tr>
<td><a href="https://github.com/redhat-et/foundation-models-for-documentation/blob/master/notebooks/finetune/Flan-T5-3B/RosaQA.ipynb">Notebook for fine-tuning FLAN-T5 (an LLM)</td>
<td>A notebook that finetunes a Flan-T5 model from HuggingFace on ROSA documentation and compares results before and after.</br>Note: large GPU is required to run it.</td>
<td>Jun 16, 2023</td>
</tr>
<tr>
<td>Pipelines [<a href="https://docs.google.com/presentation/d/1K0MECjld3-ya5ii-nMy5cOorQ-bHw2gd9j7QpVmt_iY/edit#slide=id.g25869558928_0_79">slides</a>] [<a href="https://github.com/RHRolun/pipelines_demo">demo</a>] </td>
<td>Simple pipeline example that covers the basic functionality with Elyra and a slide deck that goes through the functionality.</td>
<td>July 12, 2023</td>
</tr>
</table>

## Upcoming realease
### 1.34 - Targeted 24/10-2023
[GitHub](https://github.com/opendatahub-io/odh-dashboard/issues?q=label%3Arhods-1.34)

- Intel Habana UI Support - The accelerator can be selected from the UI for both workbenches and serving.

## Release highlights (last 3)

### 1.33 - 03/10-2023
[GitHub](https://github.com/opendatahub-io/odh-dashboard/issues?q=label%3Arhods-1.33) | [Official release documentation](https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science_self-managed/1.33/html/1.33_release_notes)
 
 - Accelerator profiles that support Intel Habana devices.

### 1.32 - 04/09-2023
[Jira](https://issues.redhat.com/browse/RHODS-11794?jql=project%20%3D%20rhods%20AND%20%22Target%20Release%22%20%3D%20RHODS_1.32.0_GA) | [Official release documentation](https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science_self-managed/1.32/html/1.32_release_notes)

- Limited availability for composite model-serving runtime based on Caikit and TGIS

### 1.31 - 14/08-2023
[Jira](https://issues.redhat.com/browse/RHODS-11371?jql=project%20%3D%20rhods%20AND%20%22Target%20Release%22%20%3D%20RHODS_1.31.0_GA) | [Official release documentation](https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science_self-managed/1.31/html/1.31_release_notes)

- Internal work for Watson.X
