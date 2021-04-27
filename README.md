## Getting Starting with Nitro Enclaves on Microsoft Windows

This repository holds the CloudFormation template for the [Getting Started with Nitro Enclaves on Microsoft Windows](https://docs.aws.amazon.com/enclaves/latest/user/nitro-enclave.html) blog.

[AWS Nitro Enclaves](https://docs.aws.amazon.com/enclaves/latest/user/nitro-enclave.html), introduced in October 2020, are isolated compute environments leveraging the power of the [AWS Nitro System](https://aws.amazon.com/ec2/nitro/) to provide isolation and attestation for sensitive data processing. Customers use Nitro Enclaves to isolate their data processing workloads, even from users with root access to the underlying EC2 instance. 

The [AWS Nitro System](https://aws.amazon.com/ec2/nitro/) itself provides unique security and performance for all latest-generation Amazon EC2 instances - including verified hardware root-of-trust due to the Nitro Controller and the Nitro Security Chip.


[AWS Nitro Enclaves](https://docs.aws.amazon.com/enclaves/latest/user/nitro-enclave.html) reduce the attack surface even further by removing all networking, persistent storage, and interactive access. The Nitro Enclave is completely separated from the host instance, even users with full root access to the host instance have no root access to the enclave. This exclusive capability enables customers to process sensitive data in an isolated compute environment, while still leveraging familiar services such as [AWS Identity and Access Management (IAM)](https://aws.amazon.com/iam/) and the [AWS Key Management Service (KMS)](https://aws.amazon.com/kms/).


For more information or for other examples of AWS Nitro Enclaves, please see the [official documentation](https://docs.aws.amazon.com/enclaves/latest/user/nitro-enclave.html) or our [overview video](https://www.youtube.com/watch?v=tRL7Y0mJqU4) on YouTube.

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

