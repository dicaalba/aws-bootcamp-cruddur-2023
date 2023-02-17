# Week 0 — Billing and Architecture

## Required Homework/Tasks

*   [x] Destroy your root account credentials, set MFA, IAM role
*   [x] Create an Admin User
*   [x] Conceptual Diagram in Lucid Charts
*   [x] Logical Architectural Diagram

*   \[\] Install and verify the AWS CLI on gitpod workspaces
*   \[\] Create Billing and Budget Alarms using CLI
*   \[\] Use EventBridge to hookup Health Dashboard to SNS and send a notification when there is a service health issue.
*   \[\] Review all the questions about each pillar in the Well Architected Tool (No specialized lens)
*   \[\] Create an architectural diagram (to the best of your ability) of the CI/CD logical pipeline in Lucid Charts

*   [x] Research the technical and service limits of specific services and how they could impact the technical path for technical flexibility.
*   [x] Open a support ticket and request a service limit

### Destroy your root account credentials, set MFA, IAM role

For this point, I created a new account on AWS, and created an organization with an account inside for reason of using this bootcamp.

![Configurando nuestro entorno de trabajo con AWS Organization y AWS Identity Center](https://cdn.hashnode.com/res/hashnode/image/upload/v1676302796261/62b29390-e57d-42bf-a204-8b5c04f97262.png?w=1600&h=840&fit=crop&crop=entropy&auto=compress,format&format=webp)

All the process is described in the following [link](https://alfalfita.cloud/configurando-nuestro-entorno-de-trabajo-con-aws-organization-y-aws-identity-center)

### Create an Admin User

I created an user admin with this permission: _**AdministratorAccess**_

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676227765389/8b4b1909-ea5b-4e14-b754-884a590f1d84.png?auto=compress,format&format=webp)

and another user with this permission: _**PowerUserAccess**_

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676227802758/ba5d28a9-fed3-43d4-af9a-b2f6eb4c924e.png?auto=compress,format&format=webp)

For both users, I activated MFA 

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676228065463/1cac86ab-ff62-466d-bbc1-f27a940d80fd.png?auto=compress,format&format=webp)

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676228105044/e6dd1a20-d995-4055-a336-177b7d00dbbf.png?auto=compress,format&format=webp)

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676228116601/43742cb5-3f69-43be-9094-260677f6fbbd.png?auto=compress,format&format=webp)

With this user, I have access to two AWS Accounts:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676228277569/fa69dd19-c772-43f4-af98-8ecdd65827f1.png?auto=compress,format&format=webp)

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676228266786/e0b8ba3f-a4f2-4fd5-a0e6-43ab58695685.png?auto=compress,format&format=webp)

### Conceptual Diagram in Lucid Charts

Created a conceptual diagram of the Cruddur application.

![](https://33333.cdn.cke-cs.com/kSW7V9NHUXugvhoQeFaf/images/e5582cdb50eee6e85ca00e65ec49c1d95bebb363e1ceb520.jpg)

### Logical Architectural Diagram

Created a logical diagram of the Cruddur application on LucidChart in this [link](https://lucid.app/lucidchart/invitations/accept/inv_a5b186e4-4213-41c3-af8d-56a97bee6fb4)

![](https://33333.cdn.cke-cs.com/kSW7V9NHUXugvhoQeFaf/images/f59e563b3b4d5d09bfd4499993e6895d036d8b2da50efda7.png)

### Install and verify AWS CLI

In my case, I installed AWS CLI on my local machine. 

![](https://33333.cdn.cke-cs.com/kSW7V9NHUXugvhoQeFaf/images/0abc633501239ffbdf54188aa8e6553ca77cfa91ca177881.png)

In the case of GitPod, I installed the following instructions as CLI: [https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html)

### Generate AWS Credentials

I configure AWS CLI with the new credentials of the users of my AWS Organization.  

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1676228239747/e5470ee8-21fe-42f1-95f9-9d0a1569b683.jpeg?auto=compress,format&format=webp)

### Create a Billing Alarm

### Create a Budget

### Open a support ticket and request a service limit

I created a support ticket for incremental elastic IPs of 5 to 10

![](https://33333.cdn.cke-cs.com/kSW7V9NHUXugvhoQeFaf/images/42b406e88113022ee0f34374095b78662e1a66bc24e76e59.png)

![](https://33333.cdn.cke-cs.com/kSW7V9NHUXugvhoQeFaf/images/95adc2a571af4d902319107b30ea3c79faad0d010b5c4978.png)

But I obtained this reply, 

![](https://33333.cdn.cke-cs.com/kSW7V9NHUXugvhoQeFaf/images/cb11a9f14294ce43dcd8a4490ceb0ab7fa58524bbe63f8fa.png)

I will try later.
