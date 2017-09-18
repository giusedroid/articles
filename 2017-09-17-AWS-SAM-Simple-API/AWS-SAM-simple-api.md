# Simple APIs with AWS SAM and Swagger!

This article will help you build a basic blog backend leveraging AWS SAM and Swagger/OpenAPI specifications.   
**Disclaimer** : No server has been harmed in the making of this post, in fact, you're about to go serverless!

## Pre-requisites
- An AWS account
- Make sure you've installed `aws cli`

## Definitions
In this secion are presented some definitions to bootstrap this post. If you are already familiar with these, feel free to skip to the next section.
### AWS SAM
The acronym SAM stands for _Serverless Application Model_. For the purposes of this article, you might think of SAM as a superset of _CloudFormation_ which enables the definition of resources specifically for serverless applications, in a simpler, less verbose way.  
Almost everything legal in CloudFormation templates is legal in SAM: the few exceptions are listed in SAM specifications and deal with CloudFormation _intrinsic functions_.  
#### Furhter Readings
Despite sufficient to go along the rest of this article, there is much more to SAM than what reported in the last paragraph, so I'd highly recommend you to skimm through the following readings.
- [AWS SAM on GitHub](https://github.com/awslabs/serverless-application-model)
- [Specifications](https://github.com/awslabs/serverless-application-model/blob/master/versions/2016-10-31.md)
- [Documentation](http://docs.aws.amazon.com/lambda/latest/dg/deploying-lambda-apps.html)
### Swagger/OpenAPI Specifications 
As [swagger.io](https://swagger.io/specification/) states
>The OpenAPI specification (formerly known as the Swagger Specification) is a powerful definition format to describe RESTful APIs. The specification creates a RESTful interface for easily developing and consuming an API by effectively mapping all the resources and operations associated with it. It’s easy-to-learn, language agnostic, and both human and machine readable.  

In practical terms and, in the scope of this article, you might think of swagger/openApi as a way to design your REST API by writing a simple yaml or json file.  
The OpenApi specifications are fully supported by AWS, in particular, it is possible to import and export your swagger apis in AWS ApiGateway, either manually via AWS Console or in an automated fashion, via CloudFormation Templates.
#### Further Readings
- [Swagger Editor](https://swagger.io/swagger-editor/)
- [Documentation](https://swagger.io/docs/)
- [Api Gateway Extensions to Swagger](http://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-swagger-extensions.html)
### Serverless

# Roadmap

## Basic Infrastructure

## Insert Lambda Here

## Deployment

### Pack
### Ship
### Run

## Bonus Level: Caching

## Conclusions