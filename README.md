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
</details>
