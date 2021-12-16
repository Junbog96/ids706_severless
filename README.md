# IDS 706 final project: Severless Data Engineering


![image](https://user-images.githubusercontent.com/51938317/146301057-3a934cf9-6851-41d6-9ad9-02363f1be0c6.png)


Project Overview
This data engineering pipleline was built for IDS 706 final project. The goal of this project is to build serverless data pipeline with Amazon Web Services, and ultimately perform a sentiment analysis with wikipedia corpus to find out if certain names are classified as having positive/negative sentiment. In this project, a number of AWS services were used: SQS, Lambda, S3, Comprehend and CloudWatch.

Conclusion
The sentiment of 24 names were analyzed through our pipeline. As a result, all 24 names, regardless of its traditional gender associations, were found to have a neutral sentiment with almost 0.99 confidence. We recognized that if the corpus captured more opinions instead of definitions and origins, the results might reflect cultural and social sentiment associated with each names.

Reference:
Rhayoung's github: https://github.com/hellonina/serverless-data-engineering
Professor Gift's github: https://github.com/noahgift/awslambda
