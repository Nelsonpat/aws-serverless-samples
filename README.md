# Serverless Samples

This repository contains samples of Serverless application code.

- ## lambda-ecs-dual-deploy 

  This AWS Lambda / ECS Dual Deploy Sample Application demonstrates the steps necessary to build a container image that runs on both AWS Lambda and on another container service like AWS Elastic Container Service (ECS).

  [[README]](./lambda-ecs-dual-deploy)

- ## serverless-rest-api

    These REST API examples demonstrate end-to-end implementations of a simple application using a serverless approach that includes CI/CD pipelines, automated unit and integration testing, and workload observability. The examples include multiple implementations of the same application using a variety of development platform and infrastructure as a code approaches. The patterns here will benefit beginners as well as seasoned developers looking to improve their applications by automating routine tasks. [[README]](./serverless-rest-api)

- ## terraform-sam-integration 

  [Terraform](https://www.terraform.io/) is an open-source infrastructure as code software tool that provides a consistent CLI workflow to manage cloud services. [AWS Serverless Application Model](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html) (SAM) is an open-source framework for building serverless applications. Teams that choose to use both Terraform and SAM need a simple way to share resource configurations between tools. [AWS Systems Manager Parameter Store](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html) (SSM) can bridge this gap by providing secure, hierarchical storage for configuration data management and secrets management. This project demonstrates how to create a simple app using Terraform, SAM and SSM Parameter Store. [[README]](./terraform-sam-integration) 

- ## apigw-private-custom-domain-name

  Implements a workaround solution for custom domain names for Amazon API Gateway private endpoints as described in the [blog post](https://georgemao.medium.com/enabling-private-apis-with-custom-domain-names-aws-api-gateway-df1b62b0ba7c)

- ## fargate-rest-api

  These examples focus on creating REST APIs with Amazon API Gateway, Amazon ECS, and AWS Fargate. The examples include CI/CD pipelines, automated unit and integration tests, as well as workload observability. The examples include multiple implementations of the same application using a variety of development platform and infrastructure as a code approaches. The patterns here will benefit beginners as well as seasoned developers looking to improve their applications by automating routine tasks. [[README]](./fargate-rest-api)

- ## multiregional-private-api

  The AWS global footprint enables customers to support applications with near zero Recovery Time Objective (RTO) requirements. Customers can run workloads in multiple regions, in a multi-site active/active manner, and serve traffic from all regions. To do so, developers often need to implement private multi-regional APIs that are used by the applications.  This example shows how to implement such a solution using Amazon API Gateway and Amazon Route 53. [[README]](./multiregional-private-api)

- ## lambda-function-url

  This example uses AWS SAM to deploy AWS Lambda URL with IAM authentication. Lambda deployed has a unique https endpoint that can be called by other parts of the application using a HTTP request with signature V4. 
  Solution also includes python script demostrating how to call the lambda endpoint [[README]](./lambda-function-url)

## Security

See [CONTRIBUTING](./CONTRIBUTING.md#security-issue-notifications) for more information.

## Code of Conduct

See [CODE OF CONDUCT](./CODE_OF_CONDUCT.md) for more information.

## License

This library is licensed under the MIT-0 License. See the [LICENSE](./LICENSE) file.
