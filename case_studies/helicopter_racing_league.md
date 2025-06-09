# Helicopter Racing League (HRL) – Case Study

Helicopter Racing League (HRL) is a global sports league for competitive helicopter racing. Each year, HRL holds the world championship and several regional league competitions where teams compete to earn a spot in the world championship. HRL offers a paid service to stream the races worldwide, providing live telemetry and predictions throughout each race. ￼

## 🏢 Company Overview
 - Business Model: Global sports league specializing in competitive helicopter racing.
 - Services: Paid streaming of races with live telemetry and predictive analytics.
 - Events: Annual world championship and multiple regional competitions.

## 💡 Solution Concept

To enhance their offerings and reach, HRL plans to: ￼
 - Migrate existing services to a new platform to leverage managed AI and ML services for race predictions.
 - Serve content (both real-time and recorded) closer to users, especially in emerging regions, to reduce latency and improve user experience. ￼ ￼

## 🖥️ Existing Technical Environment
 - Cloud Strategy: Public cloud-first; core mission-critical applications run on the current public cloud provider.
 - Content Creation: Video recording and editing are performed at race tracks; content is encoded and transcoded in the cloud as needed.
 - Storage: Existing content is stored in an object storage service on the current public cloud provider.
 - Processing: Video encoding and transcoding are performed on VMs created for each job.
 - Race Predictions: Utilize TensorFlow running on VMs in the current public cloud provider.
 - Connectivity: Enterprise-grade connectivity and local compute are provided by truck-mounted mobile data centers. ￼ ￼ ￼

## 📈 Business Requirements
 - Expose predictive models to partners.
 - Enhance predictive capabilities during and before races, including:
 - Race results
 - Mechanical failures
 - Crowd sentiment
 - Increase telemetry and generate additional insights.
 - Measure fan engagement with new predictions.
 - Enhance global availability and quality of broadcasts.
 - Increase the number of concurrent viewers. ￼

## 🛠️ Technical Requirements
 - Maintain or increase prediction throughput and accuracy.
 - Reduce viewer latency.
 - Increase transcoding performance.
 - Develop real-time analytics of viewer consumption patterns and engagement.
 - Create a data mart to process large volumes of race data.
 - Minimize operational complexity.
 - Ensure compliance with regulations.
 - Establish a merchandising revenue stream. ￼

## 🗣️ Executive Statement

“Our CEO, S. Hawke, wants to bring high-adrenaline racing to fans all around the world. We listen to our fans, and they want enhanced video streams that include predictions of events within the race (e.g., overtaking). Our current platform allows us to predict race outcomes but lacks the facility to support real-time predictions during races and the capacity to process season-long results.” ￼

## Reference
 - [helicopter_racing_league](https://services.google.com/fh/files/blogs/master_case_study_helicopter_racing_league.pdf)
 