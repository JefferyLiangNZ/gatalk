* Your opinion matters to me

** Security and DR related practices 
- such as CIS benchemark for hardening Docker/Linux os;
- Incremental backup process in AWS S3 or Glacier;
- Bastion-Server access to EC2 or Use SSM for random commands, or batch jobs;
- Securing access to Console, Developer credential, using MFA;
- How do GA enforce the rotation of RSA-Keypair/Deployment secrets in Vault automatically;
- How do GA enable Developer's Security Session Token for Developers, 
- What are the critical scenarioes do GA enforce MFA (like delete Bucket, files)?; 
- which "conditions"(in policy configuration) you have ever used for restricting S3, SNS, EC2, Lambda;
- What's your key auditing areas for Cloudtrail/AWS Config;

** DevOps /Production Monitoring
(Implement RDS changset capture -- Row level change;
(Monitoring Cloudwatch Metrics, also disk space/CPU credits;
(Monitoring Application Logs;
(Mock environment for unittest;
(important metrics/ keywords to check/filter;
(Infra test specs;

** Management
(Resource Naming, Tagging, Cost Tagging;
(Identity or IAM best practices;
(How you manage/group servics like SecurityGroup, Role, are there hiearchy? ;
(Multi-Stage resource separation;

** Authentication,Authorization
( Integration such as AzureAD, GooglePlus;
(JWT, API Key, User cred, Signed HTTP Request;

** What's your Do's, Don'ts, Gotchas and lessons that you have learned over the years
or your curated cheatsheets