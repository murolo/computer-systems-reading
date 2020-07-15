# **[Serverless in the Wild: Characterizing and Optimizing the Serverless Workload at a Large Cloud Provider](https://arxiv.org/pdf/2003.03423.pdf)**

## Abstract
Function as a Service (FaaS) has been gaining popularity as a way to deploy computations to serverless backends in the cloud. This paradigm shifts the complexity of allocating and provisioning resources to the cloud provider, which has to provide the illusion of always-available resources (i.e., fast function invocations without cold starts) at the lowest possible resource cost. Doing so requires the provider to deeply understand the characteristics of the FaaS workload. Unfortunately, there has been little to no public information on these characteristics. Thus, in this paper, we first characterize the entire production FaaS workload of Azure Functions. We show for example that most functions are invoked very infrequently, but there is an 8-order-of-magnitude range of invocation frequencies. Using observations from our characterization, we then propose a practical resource management policy that significantly reduces the number of function cold starts, while spending fewer resources than state-of-the-practice policies.

## Problem

## Contribution
• A detailed characterization of the entire production FaaS workload at a large cloud provider;

• A new policy for reducing the number of cold start function executions at a low resource provisioning cost;

• Extensive simulation and experimental results based on real traces showing the benefits of the policy;

• An overview of our implementation in Azure Functions;

• A large sanitized dataset containing production FaaS traces.

## Evaluation

## Conclusion

## Review

## Related Work

## Links