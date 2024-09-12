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

## EC2 (ECS)

## Amazon Elastic Container Registry (ECR)

## S3
<details>
  <summary>Summary</summary>
  <br/>
  
  + S3 Bucket Policies is a form of resource policy.
</details>

## Gateway

