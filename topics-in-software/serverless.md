---
description: Mostly (but not entirely) AWS Lambda related
---

# Serverless

====== Serverless & AWS Lambda ======

===== Articles & Blog Posts =====

==== General Serverless ====


  * [[https://medium.com/digital-anatomy/five-facets-of-flow-strategy-96a737243ee5|Five Facets of Flow Strategy]] - A broad set of things to consider as we move into a serverless, event-driven network of small pieces.
  * [[https://medium.com/@PaulDJohnston/serverless-best-practices-b3c97d551535|Serverless Best Practices]]
  * [[https://github.com/cristim/serverless-failure-stories|Serverless Failure Stories]]
  * [[https://martinfowler.com/articles/serverless.html|Serverless Architectures]]
  * [[https://read.acloud.guru/https-medium-com-timawagner-serverless-mullet-architectures-212487bc75c?source=rss----cf64e15dbc8c---4&gi=13182535f800|Serverless Mullet Architectures]]
  * [[https://blog.alexellis.io/getting-started-with-the-plonk-stack-and-serverless/|Getting Started with the PLONK Stack and Serverless 2.0]] - Prometheus, Linkerd, OpenFaaS, NATS, Kubernetes

==== AWS Lambda ====

  * [[http://www.tbray.org/ongoing/When/201x/2018/12/09/Serverlessness|Serverlessness]]- Series of blog posts from Amazon's Tim Bray, based on his re:invent 2018 talk.
  * [[https://theburningmonk.com/2019/02/lambda-optimization-tip-enable-http-keep-alive/|Lambda optimization tip – enable HTTP keep-alive]] - For DynamoDB specifically
  * [[https://advancedweb.hu/2019/04/10/limiting_lambda/|AWS: How to limit Lambda and API Gateway scalability]]: Cost control in the cloud.
  * [[https://medium.com/capital-one-tech/best-practices-for-aws-lambda-container-reuse-6ec45c74b67e|Best Practices for AWS Lambda Container Reuse]]: "Optimizing Warm Starts When Connecting AWS Lambda to Other Services"
  * [[https://www.cookieshq.co.uk/posts/a-useful-tool-for-building-serverless-ruby-apps-with-aws-lambda|A useful tool for building serverless Ruby apps with AWS Lambda]]: Introducing Ruby_Lambda.
  * [[https://aws.amazon.com/blogs/architecture/ten-things-serverless-architects-should-know/|https://aws.amazon.com/blogs/architecture/ten-things-serverless-architects-should-know/]]
  * [[https://medium.com/predict/lambda-optimization-tip-enable-http-keep-alive-ef7aa7880554|Lambda optimization tip — enable HTTP keep-alive]] - Including notes on how to test the optimization
  * [[https://aws.amazon.com/blogs/compute/designing-durable-serverless-apps-with-dlqs-for-amazon-sns-amazon-sqs-aws-lambda/|Designing durable serverless apps with DLQs for Amazon SNS, Amazon SQS, AWS Lambda]]
  * [[https://medium.com/@jlaitio/aws-serverless-websockets-introduction-around-the-pitfalls-f623518635df|AWS Serverless WebSockets — Introduction Around the Pitfalls]]
  * [[https://github.com/nsriram/lambda-the-cli-way|AWS Lambda the CLI Way]] - In-depth tutorial that does everything from the command line.

==== Development ====

  * [[https://dev.to/ibmdeveloper/serverless-functions-with-webassembly-modules-343e|Serverless Functions With WebAssembly Modules ]]
  * [[https://blog.alexellis.io/faas-for-the-rubyist/|FaaS for the Rubyist]] - Self-hosting with OpenFAAS.
  * [[https://theodo-uk.github.io/sls-dev-tools/|Serverless-Dev-Tools]] - Console-based management for AWS Lambda.

==== Security ====

  * [[http://flaws2.cloud/|flAWS2.cloud]] -Interactive security training that lets you play the attacker or defender roles.

==== Logging ====

  * [[https://www.datadoghq.com/blog/datadog-for-serverless/|Introducing Datadog for serverless]]

==== AWS API Gateway ====

  * [[https://www.alexdebrie.com/posts/api-gateway-elements/|A Detailed Overview of AWS API Gateway]]

==== Deployment ====

  * [[https://serverless.pub/deploy-frontend-to-s3-and-sar/?utm_content=88841955&utm_medium=social&utm_source=twitter&hss_channel=tw-920289756919074817|How to use CloudFormation to deploy Frontend Apps to S3 and Serverless Application Repository]]: A nice workaround for some AWS limitations.
  * [[https://github.com/serverless-components/aws-app-sync|Serverless AppSync Component]]: "The AppSync Serverless Component allows you to easily and quickly deploy GraphQL APIs on AWS, and integrate them with AWS Lambda, DynamoDB & others."

==== Testing ====

  * [[https://vacationtracker.io/blog/big-bad-serverless-vendor-lock-in/|Fighting vendor lock-in and designing testable serverless apps using hexagonal architecture]]

=====Other Tools =====


  * [[https://github.com/jeremydaly/lambda-warmer|Lambda Warmer]] - Optimizer for Lambda cold starts
  * [[https://aws.amazon.com/blogs/developer/announcing-ruby-build-support-for-aws-sam-cli/|Announcing Ruby build support for AWS SAM CLI]]
