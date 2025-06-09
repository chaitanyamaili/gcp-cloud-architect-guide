# TerramEarth – Case Study

TerramEarth manufactures heavy equipment for the mining and agricultural industries. They currently have over 500 dealers and service centers in 100 countries. Their mission is to build products that make their customers more productive. ￼ ￼

## 🏢 Company Overview
 - Industry: Mining and Agricultural Equipment Manufacturing
 - Global Presence: 500+ dealers and service centers across 100 countries
 - Fleet Size: 2 million vehicles in operation, with 20% annual growth ￼

## 💡 Solution Concept

TerramEarth aims to enhance its fleet management services by leveraging Google Cloud’s capabilities. Their objectives include:
 - Improving predictive maintenance to reduce vehicle downtime
 - Enhancing development workflows for faster feature deployment
 - Creating a scalable platform for partners to build custom applications
 - Gradually migrating legacy systems to the cloud without disrupting operations ￼ ￼

## 🖥️ Existing Technical Environment
 - Data Collection:
 - Vehicles collect telemetry data from various sensors during operation.
 - A subset of critical data is transmitted in real-time for fleet management.
 - The remaining data is compressed and uploaded daily when vehicles return to base.
 - Each vehicle generates approximately 200 to 500 MB of data per day. ￼ ￼
 - Infrastructure:
 - Vehicle data aggregation and analysis infrastructure resides in Google Cloud.
 - Sensor data from manufacturing plants is sent to private data centers housing legacy systems.
 - Private data centers have multiple network interconnects configured to Google Cloud. ￼
 - Applications:
 - Web frontend for dealers and customers runs in Google Cloud, providing access to stock management and analytics.

## 📈 Business Requirements
 - Predict and detect vehicle malfunctions to enable just-in-time repairs.
 - Decrease cloud operational costs and adapt to seasonal demand fluctuations.
 - Increase speed and reliability of the development workflow.
 - Allow remote developers to be productive without compromising security.
 - Create a flexible and scalable platform for developers to build custom API services for dealers and partners. ￼ ￼

## 🛠️ Technical Requirements
 - Develop a new abstraction layer for HTTP API access to legacy systems to facilitate gradual cloud migration.
 - Modernize CI/CD pipelines to support deployment of container-based workloads in scalable environments.
 - Enable developers to run experiments without compromising security and governance.
 - Create a self-service portal for internal and partner developers to manage projects and access API endpoints.
 - Implement cloud-native solutions for key and secrets management, optimizing for identity-based access.
 - Improve and standardize tools necessary for application and network monitoring and troubleshooting. ￼

## 🗣️ Executive Statement

“Our competitive advantage has always been our focus on the customer, with our ability to provide excellent customer service and minimize vehicle downtimes. After moving multiple systems into Google Cloud, we are seeking new ways to provide best-in-class online fleet management services to our customers and improve operations of our dealerships. Our 5-year strategic plan is to create a partner ecosystem of new products by enabling access to our data, increasing autonomous operation capabilities of our vehicles, and creating a path to move the remaining legacy systems to the cloud.”

## Reference
 - [terramearth](https://services.google.com/fh/files/blogs/master_case_study_terramearth.pdf)