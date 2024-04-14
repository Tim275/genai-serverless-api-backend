## Architecture Diagramm


![bedrockdark](https://github.com/Tim275/genai-serverless-api-backend/assets/117520669/0ef8ff02-707b-4e94-a484-f1f5968fa02e)


# sam-gen-ai

Congratulations, you have just created a Serverless "Hello World" application using the AWS Serverless Application Model (AWS SAM) for the `python3.11` runtime, and options to bootstrap it with [**AWS Lambda Powertools for Python**](https://awslabs.github.io/aws-lambda-powertools-python/latest/) (Lambda Powertools) utilities for Logging, Tracing and Metrics.

Powertools is a developer toolkit to implement Serverless best practices and increase developer velocity.


## Powertools features

Powertools provides three core utilities:

* **[Tracing](https://awslabs.github.io/aws-lambda-powertools-python/latest/core/tracer/)** - Decorators and utilities to trace Lambda function handlers, and both synchronous and asynchronous functions
* **[Logging](https://awslabs.github.io/aws-lambda-powertools-python/latest/core/logger/)** - Structured logging made easier, and decorator to enrich structured logging with key Lambda context details
* **[Metrics](https://awslabs.github.io/aws-lambda-powertools-python/latest/core/metrics/)** - Custom Metrics created asynchronously via CloudWatch Embedded Metric Format (EMF)

Find the complete project's [documentation here](https://awslabs.github.io/aws-lambda-powertools-python).

### Installing AWS Lambda Powertools for Python

With [pip](https://pip.pypa.io/en/latest/index.html) installed, run: 

```bash
pip install aws-lambda-powertools
```
