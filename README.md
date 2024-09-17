# AWS knowledge
## IAM
### User
<details>
  <summary>Summary</summary>
  <br/>
  
  + There's the 5000 IAM user limit per account.
</details>

### Group
<details>
  <summary>Summary</summary>
  <br/>
  
  + Group are not a true identity.
  + Group just container which contains Users.
  + A resource policy cannot grant acess to an group.
</details>

### Role
<details>
  <summary>Summary</summary>
  <br/>

  + Can't log in to a Role.
  + Role has two types of policy which can be attach: _Trust Policy_ and _Permissions Policy_.
</details>

## Organization
### Service Control Policies
<details>
  <summary>Summary</summary>
  <br/>
  
  + Service Control Policies (SCPs) are just a boundary. They define the limit of what is and isn't allowed
  + The management account is special and it's unaffected by any service control policies.
  + They don't grant any permissions.
  + The default of SCPs is FullAWSAccess.
</details>

## CloudTrail
<details>
  <summary>Summary</summary>
  <br/>
  
  + Enable by default on AWS account, but it's only the 90-day event history.
  + Don't get any storage in S3 unless configure a trail.
  + Store management events only by default.
  + IAM, STS, CloudFront log their data as global service events at US East 1 and trail will need to be enable to capure that data.
  + Not real-time.
</details>

## Amazon Elastic Container Service (ECS)
<details>
  <summary>What is AWS ECS</summary>
  <br/>

</details>
<details>
  <summary>Concepts</summary>
  <br/>

</details>
<details>
  <summary>ECS terminology</summary>
  <br/>

  + **Task Definition -** A blueprint that describes how a Docker container should launch1.
  + **Task -** This is a running container with the settings defined in the Task Definition. It can be thought of as an “instance” of a _**Task Definition**_.
  + **Service -** Defines long running tasks of the same Task Definition. This can be 1 running container or multiple running containers all using the same _**Task Definition**_.
  + **Cluster -** A logic group of _**EC2**_ instances.
  + **Container Instance -** This is just an _**EC2**_ instance that is part of an _**ECS Cluster**_ and has docker and the ecs-agent running on it.

</details>

## Amazon Elastic Container Registry (ECR)
<details>
  <summary>What is AWS ECR</summary>
  <br/>
Amazon Elastic Container Registry (ECR) is a fully managed container registry service that makes it easy for developers to store, manage, and deploy Docker container images.

</details>

## Amazon Simple Storage Service (S3)
<details>
  <summary>What is AWS S3</summary>
  <br/>
  S3 is an object storage service provided by AWS. It offers industry-leading scalability, data availability, security, and performance.
  
</details>
<details>
  <summary>Buckets and Objects</summary>
  <br/>
  
  
</details>

### Data Management
<details>
  <summary>Versioning</summary>
  <br/>
  
  
</details>
<details>
  <summary>Object Lock</summary>
  <br/>
  
  
</details>

### Security
<details>
  <summary>Bucket Policies</summary>
  <br/>
  
  
</details>
<details>
  <summary>Access Control Lists (ACLs)</summary>
  <br/>
  
  
</details>
<details>
  <summary>Encryption</summary>
  <br/>
  
  
</details>

### Performance
<details>
  <summary>High-Performance Storage</summary>
  <br/>
  
  
</details>

## Gateway

<details>
  <summary>What is AWS Gateway</summary>
  <br/>

</details>
