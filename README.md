# Oxycloud 

It's just **THE ULTIMATE** cloud storage you can find in the entire universe! 🌌🚀

Made by [Caronte Gianluca](https://github.com/Janluke0) and [Luca Ferrari](https://github.com/frittatelle) for the [Software Engineering Course](https://simonemerlini.it/sweng/) 

Key technologies:
    - Built on top of [Amazon Web Services](https://aws.amazon.com/)
    - Infrastracture As Code, with [Terraform](https://www.terraform.io/)
    - Web frontend made with [React](https://reactjs.org/)
    - [Lambda functions](https://aws.amazon.com/lambda/) written in [Python](https://python.org/)

Key features:
    - Storage space
        - Settable at user level
        - Granulary checked
    - Limited bandwith consumption
        - Direct usage of S3 trought presigned authorization
        - Caching
        - Preventive blocking of the upload in case of out of space 
    - Fully scalable
        - Cloudfront 
        - API Gateway
        - S3 
        - DynamoDB
    - IaC for fast and automatable DevOps
