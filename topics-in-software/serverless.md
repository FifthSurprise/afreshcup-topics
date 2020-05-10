---
description: Mostly (but not entirely) AWS Lambda related
---

# Serverless & AWS Lambda

## Articles & Blog Posts

### General Serverless


  * [Five Facets of Flow Strategy](https://medium.com/digital-anatomy/five-facets-of-flow-strategy-96a737243ee5) - A broad set of things to consider as we move into a serverless, event-driven network of small pieces.
  * [Serverless Best Practices](https://medium.com/@PaulDJohnston/serverless-best-practices-b3c97d551535)
  * [Serverless Failure Stories](https://github.com/cristim/serverless-failure-stories)
  * [Serverless Architectures](https://martinfowler.com/articles/serverless.html)
  * [Serverless Mullet Architectures](https://read.acloud.guru/https-medium-com-timawagner-serverless-mullet-architectures-212487bc75c?source=rss----cf64e15dbc8c---4&gi=13182535f800)
  * [Getting Started with the PLONK Stack and Serverless 2.0](https://blog.alexellis.io/getting-started-with-the-plonk-stack-and-serverless/) - Prometheus, Linkerd, OpenFaaS, NATS, Kubernetes

### AWS Lambda

  * [Serverlessness](http://www.tbray.org/ongoing/When/201x/2018/12/09/Serverlessness)- Series of blog posts from Amazon's Tim Bray, based on his re:invent 2018 talk.
  * [Lambda optimization tip – enable HTTP keep-alive](https://theburningmonk.com/2019/02/lambda-optimization-tip-enable-http-keep-alive/) - For DynamoDB specifically
  * [AWS: How to limit Lambda and API Gateway scalability](https://advancedweb.hu/2019/04/10/limiting_lambda/): Cost control in the cloud.
  * [Best Practices for AWS Lambda Container Reuse](https://medium.com/capital-one-tech/best-practices-for-aws-lambda-container-reuse-6ec45c74b67e): "Optimizing Warm Starts When Connecting AWS Lambda to Other Services"
  * [A useful tool for building serverless Ruby apps with AWS Lambda](https://www.cookieshq.co.uk/posts/a-useful-tool-for-building-serverless-ruby-apps-with-aws-lambda): Introducing Ruby_Lambda.
  * [https://aws.amazon.com/blogs/architecture/ten-things-serverless-architects-should-know/](https://aws.amazon.com/blogs/architecture/ten-things-serverless-architects-should-know/)
  * [Lambda optimization tip — enable HTTP keep-alive](https://medium.com/predict/lambda-optimization-tip-enable-http-keep-alive-ef7aa7880554) - Including notes on how to test the optimization
  * [Designing durable serverless apps with DLQs for Amazon SNS, Amazon SQS, AWS Lambda](https://aws.amazon.com/blogs/compute/designing-durable-serverless-apps-with-dlqs-for-amazon-sns-amazon-sqs-aws-lambda/)
  * [AWS Serverless WebSockets — Introduction Around the Pitfalls](https://medium.com/@jlaitio/aws-serverless-websockets-introduction-around-the-pitfalls-f623518635df)
  * [AWS Lambda the CLI Way](https://github.com/nsriram/lambda-the-cli-way) - In-depth tutorial that does everything from the command line.
  * [The Serverless Software Development Lifecycle](https://www.trek10.com/blog/the-serverless-software-development-lifecycle) - "A quick look at building, testing, and deploying AWS Lambda based apps and how to set yourself up for success."

### OpenFaaS

  * [Meet faasd - portable Serverless without the complexity of Kubernetes](https://www.openfaas.com/blog/introducing-faasd/)

### Development

  * [Serverless Functions With WebAssembly Modules ](https://dev.to/ibmdeveloper/serverless-functions-with-webassembly-modules-343e)
  * [FaaS for the Rubyist](https://blog.alexellis.io/faas-for-the-rubyist/) - Self-hosting with OpenFAAS.
  * [Serverless-Dev-Tools](https://theodo-uk.github.io/sls-dev-tools/) - Console-based management for AWS Lambda.
  * [24 open source tools for the serverless developer: Part 1](https://aws.amazon.com/blogs/opensource/24-open-source-tools-for-the-serverless-developer-part-1/) and [Part 2](https://aws.amazon.com/blogs/opensource/24-open-source-tools-for-the-serverless-developer-part-2/)

### Security

  * [flAWS2.cloud](http://flaws2.cloud/) -Interactive security training that lets you play the attacker or defender roles.

### Logging

  * [Introducing Datadog for serverless](https://www.datadoghq.com/blog/datadog-for-serverless/)

### AWS API Gateway

  * [A Detailed Overview of AWS API Gateway](https://www.alexdebrie.com/posts/api-gateway-elements/)

### Deployment

  * [How to use CloudFormation to deploy Frontend Apps to S3 and Serverless Application Repository](https://serverless.pub/deploy-frontend-to-s3-and-sar/?utm_content=88841955&utm_medium=social&utm_source=twitter&hss_channel=tw-920289756919074817): A nice workaround for some AWS limitations.
  * [Serverless AppSync Component](https://github.com/serverless-components/aws-app-sync): "The AppSync Serverless Component allows you to easily and quickly deploy GraphQL APIs on AWS, and integrate them with AWS Lambda, DynamoDB & others."

### Testing

  * [Fighting vendor lock-in and designing testable serverless apps using hexagonal architecture](https://vacationtracker.io/blog/big-bad-serverless-vendor-lock-in/)

### Other Tools

  * [Lambda Warmer](https://github.com/jeremydaly/lambda-warmer) - Optimizer for Lambda cold starts
  * [Announcing Ruby build support for AWS SAM CLI](https://aws.amazon.com/blogs/developer/announcing-ruby-build-support-for-aws-sam-cli/)
