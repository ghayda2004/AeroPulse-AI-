# AeroPulse AI
**Cloud-Native Predictive Maintenance & Agentic AI for Aircraft Engines**

AeroPulse AI is an end-to-end AWS cloud project designed to simulate aircraft engine telemetry, predict Remaining Useful Life (RUL), and automate maintenance workflows through actionable AI agents.

Using the NASA C-MAPSS turbofan engine dataset, the platform replays sensor measurements as real-time IoT streams, processes telemetry through Apache Kafka (Amazon MSK), and builds a scalable data lake using Amazon S3, AWS Glue, and Amazon Data Firehose.

Amazon SageMaker powers the machine learning lifecycle, from feature engineering and XGBoost training to model evaluation, deployment, and real-time inference.

An AI agent powered by Amazon Bedrock analyzes operational risk and takes controlled actions, including increasing engine monitoring frequency and generating maintenance inspection requests.

Amazon Athena and QuickSight provide analytical dashboards for engine health, RUL predictions, and maintenance activities.

**Core technologies:** AWS IoT Core, ECS Fargate, Amazon MSK, Data Firehose, S3, AWS Glue, SageMaker, DynamoDB, Bedrock, Lambda, Athena, QuickSight, Python, Docker, XGBoost.
