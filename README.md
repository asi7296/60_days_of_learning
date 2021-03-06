# Anish Sujanani - 60 Days of Learning

*All directories will contain notes as per the overview in this file*

## Topics:
/AppSec - Application Security  
/Identity - Authentication and Authorization  
/CloudInfra - AWS, Operating Systems

## Each directory will contain .md files for each day that I explore a topic within that domain. Files include notes, references, PoCs.

------------
## Tracking
### Day 1 - `notes written`
**Identity:**
  - Identity Solution Architectures
  - Good authenticaion practices + Server Statelessness / Client Statelessness
  - Building custom permission matrices 
  - NodeJS libraries for ABAC/RBAC
  - Centralised solutions to be explored in days to come
------------
### Day 2 - `notes written`
**Identity:**
  - Building RBAC with NodeJS-Express from scratch + PoC
  - Custom RBAC becomes an issue as resources/roles/actions grow - need to centralise
  - Centralised solutions speak over the network either through SAML or OAuth2.0, looking at common solutions
------------
### Day 3 - `notes written`
**Identity:**
  - Read the OAuth2.0 Specification - [RFC-6749](https://tools.ietf.org/html/rfc6749)
  - Started implementation on a from-scratch OAuth2.0 Authorization Server - trying to implement above RFC
  - Looked into OAuth Flows - resources linked in notes
  - Came across Web Authn - a new standard for bringing MFA/biometrics to browsers & PKI for web-app authentication
  - Might branch out and explore Web-Authn too?
------------
### Day 4 - `notes written`
**Identity:**
  - Implemented OAuth2.0 Authorization Code Flow from scratch by following the RFC - using NodeJS 
  - Servers were hosted on AWS, so the IP addresses in the code are no longer the same 
  - Got started writing blog post about this 
------------
### Day 5 - `notes written`
**App-Sec:**
  - Looked into NodeJS Security implementations
  - NPM Library Auditing
------------
### Day 6 - `notes written`
**App-Sec:**
  - iFrame embedding and the PostMessage API for sandboxing JS
  - [Box-JS](https://www.npmjs.com/package/box-js) for offline analysis of JS files
  - ELF Format - Section-Segment mapping during linking/process loading + Padding Injection
  - [OWASP CheatSheet Project](https://www.sans.org/reading-room/)
  - [SANS Reading Room](https://www.sans.org/reading-room/)

**Identity**
  - Blog Post - in progress on OAuth2.0 from scratch
------------
### Day 7 - `notes written`
**App-Sec:**
  - Javascript Internals - Butterfly objects, boxing
  - WebKit security Issues 

**Identity:**
  - Read about integrating AWS Cognito with API Gateway 
------------
### Day 8 - `notes written`
**App-Sec:**
  - CSRF Defence Patterns - Synchonizer Token vs. Double Submit Cookies
  - State of NodeJS Security
  - SnykIO and avoid common Node Security Issues
  - NodeJs Security Practices - Helmet for Express
------------
### Day 9
**App-Sec:**
  - Read up on a few NPM lib and PIP lib disclosures on Snyk
  - [Memory leak errors with NodeJS](https://www.youtube.com/watch?v=hliOMEQRqf8)
------------
### Day 10
**App-Sec:**
  - CodeQL for discovering bad code / semantic patterns in codebases
  - Security Guidelines in Open-Source Ecosystems - [Open Source Security Foundation](https://openssf.org/)

**Identity:**
- Better IAM policy development for AWS S3
------------
### Day 11
**App-Sec:**
  - [CodeQL - looking for the RSysLog strcpy issues](https://www.youtube.com/watch?v=AMzGorD28Ks)
  - [CodeQL - Looking for the Apache Struts Insecure XML Deserialization](https://www.youtube.com/watch?v=nvCd0Ee4FgE)
  - Started playing around with CodeQL on my older repos
------------
### Day 12
**App-Sec:**
  - Studied more CodeQL queries
  - Started studying C Programming POSIX system calls & threading / sync security issues
  - The plan is to build up CodeQL to look for these patters, eg. open() after access() without checking for whether the directory was modified or symbolic link checks  
------------  
### Day 13
**Identity:**
  - [Wrote a blog post on custom OAuth with NodeJS](https://medium.com/bugbountywriteup/oauth2-0-from-scratch-auth-code-flows-and-rbac-with-nodejs-dda9b51a4c36)  

**App-Sec:**
  - Learnt about Linux system call race conditions and TOCTOU vulns
  - learnt about prototype pollution in JS objects
------------  
### Day 14 `notes written` 
**App-Sec:**
  - Deep dive into Memcached security - debug interface, API, LRU cache crawling, authentication with SASL
  - Deep dive into AWS Elasticache security and best practices
  - Active Directory Internals and Security Measures
------------  
### Day 15 `notes written` 
**App-Sec:**
  - Active Directory Security - LDAP, SPN Scans, Transitive-trusts and Recon
  - Active Directory Security - AS_REQ for TGT, Kerberos Pre-Auth 
  - Active Directory Security - AS-REP Roast, Kerberoast, Silver Ticket, Golden Ticket, Sekeleton Keys
------------  
### Day 16  
**App-Sec:**
  - Got started writing my own BurpSuite plugins  


**Cloud-Infra:**
  - Read up on AWS S3 for the SAA
  - Started learning about Windows Servers 
------------  
### Day 17  
**App-Sec:**
  - Continued writing custom plugins  
  - More PortSwigger Web Academy excercises
------------  
### Day 18  
**App-Sec:**
  - Did more PortSwigger Web Academy Challenges
  - Read about web cache best practices 
  - Callbacks, Promises and async/await with NodeJS
------------  
### Day 19
**App-Sec:**
  - Learnt more about SSL accelerators/terminating proxies
  - Continued working on the custom BurpSuite plugin 
  - Watched an [excellent video on API endpoint discovery and enumeration](https://www.youtube.com/watch?v=fvcKwUS4PTE)
------------  
### Day 20
**App-Sec:**
  - [Serverless Application Security - Lambdas and GraphQL](https://www.youtube.com/watch?v=wCRkmeLYhYQ&t=527s)

**Cloud-Infra:**
  - Learnt about AWS Serverless applications - Lambdas - Functions as a Service
  - Learnt about connecting Lambda backends with API Gateway
------------  
### Day 21
**App-Sec:**
- [Microsoft - Guidance on responding to Security Incidents](https://docs.microsoft.com/en-us/previous-versions/tn-archive/cc700825(v=technet.10)?redirectedfrom=MSDN)
- [SANS Paper on Mobile AV](https://www.sans.org/reading-room/whitepapers/mobile/paper/38990)
- Continued course on IR
------------  
### Day 22
**App-Sec:**
- Continued course on IR 
- Continued Web Lab Excercises   
**Practiced LeetCode problems - 1431, 1470 1480**

------------  
### Day 23
**App-Sec:**
- Continued course on IR  
- Learnt about NodeJS Dependency audit as part of the build chain  
- Started building the backend API for the HTTP Analysis plugin  
**Practiced LeetCode problems - 520, 705, 125**

------------  
### Day 24
**Practiced LeetCode problems - 1534, 1290, 1464**

------------  
### Day 25
**Practiced LeetCode problems - 905, 1450**  

**CloudInfra** 
- Learnt about custom headers and Bearer/token auth for nodejs backend services 
  
**AppSec**
- Continued course on IR procedures and baselining IT assets
- Learnt about Layer 2 Network Unicast ARP implementation

------------  
### Day 26
**Practiced LeetCode problems - 804, 1351**  

**CloudInfra** 
- Learnt about setting up Windows Servers - AD/DHCP/DNS and Backups   

------------  
### Day 27
**Practiced LeetCode problems - 728, 1299, 1475**  

**CloudInfra** 
- Learnt about routing protocols for better Quality of Service per application

------------  
### Day 28
**Learnt about python internals - internal class format functions and their calls through f-strings**  

**AppSec**
- Learnt about Linux SecComp and system call programming

------------  
### Day 29

**CloudInfra**
- Deep dive on digital signature verification and TLS session establishment

**AppSec**
- Continued IR course

------------  
### Day 30

**CloudInfra**
- Learnt about AWS Key Management Service and Cognito  

**AppSec**
- Looked into blogs for certs

------------  
### Day 31

**AppSec**
- Studied Linux signal interface and shared memory

------------  
### Day 32
**Cloud-Infra:**
  - Learnt about AWS Message Queueing services
  - Learnt about building scalable web architecture - managing sessions and scaling out servers

------------  
### Day 33
**Cloud-Infra:**
  - Read AWS Route 53 and Cloudfront for the SAA
  - Learnt about and implemented bloom filters 

------------  
### Day 34
**App-Sec:**
  - Performed a source code audit excercise for a dummy PHP file store application, found all intended bugs except for one to do with custom JSON parsers used for the included JWT libraries
  - Looked into projects that automate source code audit 

------------  
### Day 35
**App-Sec:**
  - Learnt more about securing applications in prob, specifically back-ends for mobile apps

**Started a course on Mathematics for Computer Science** 

------------  
### Day 36

**Practiced Leetcode problems: 1295, 1441**  
**Explored bloom filter - error rate and variation with filter length and number of hashing algorithms**  
**Learnt about Huffman Code - tree generation, got started with implementation**   
**Table doubling algorithms in constant time for Python**  
**Solved a few problems on propositional logic**  

------------  
### Day 37

**Solved problems on propositional logic, started looking into propositional equivalences and De Mogran Laws for proofs**  

**Practiced Leetcode problems: 1305, 1323, 1021, 654, 657**  

**Python replace() takes a third int param which controls how many chars are replaced**  

**App-Sec:**
  - Learnt about how the compiler and OS provide stack protection - canaries, page permissions, non-ex stack, baggy bounds checking

------------  
### Day 38

**App-Sec:**
  - Continued course on IR 

**CloudInfra:**
  - AWS SAA - Solved sample questions on EC2, read through whitepapers

**Solved more problems on deriving mathematical proof with De Morgan's laws**

------------  
### Day 39

**CloudInfra:**
  - Learnt more about distributed computation and verification
  - Learnt about AWS database models 

**Solved problems on predicate logic**

------------  
### Day 40

**Solved leetcode problems on trees: 701 (got a Python 99.89% than the rest), 1528 (faster than 96.42% other solutions)**  

**App-Sec:**
  - Last set of video lectures for the IR course

------------  
### Day 41

**CloudInfra:**
 - Securing enterprise web servers
 - Learnt about AWS Elastic Beanstalk

------------  
### Day 42

**App-Sec:**
 - Securing shared drives and FTP shares 
 - Best practices for crontab-enabled scripts 

------------  
### Day 43

**Solved Leetcode - 1512, 1313, 1486, 1389, 1395**  
**Watche Bjarne Stroustrup's talks on optimizing C++ and simplifying design**

**App-Sec:**
 - Learnt more about WebDAV and Windows Server Management
 
------------  
### Day 44
 **Looked into better practices and custom libraries for competitive programming**  


**CloudInfra:**
 - Watched a SANS talk on the top 20 controls for enteprise infrastructure 

------------  
### Day 45

**CloudInfra:**
 - Learnt about setting up AWS VPCs, subnets, internet gateways, routers and security groups
  
------------  
### Day 46

**CloudInfra:**
  - Got into the practical bits - created VPCs, subnets, security groups, internet gateways, NACL and built network 
  - Did it manually, plus started playing around with cloudformation to automate those builds
  - Learnt about better security practices on security groups and NACLs

------------  
### Day 47

**CloudInfra:**
  - Understood AWS Users, Groups, Roles and Policies 
  - Started writing basic policies for users and resources 
  - Learnt about authentication and authorization for API Gateways and Lambdas 
  - Trying to set up IAM based authorization on API Gateway routes

------------  
### Day 48

**CloudInfra:**
  - Set up my first serverless application using AWS Lambda, API Gateways with IAM for authentication and authorization
  - Learnt about AWS Security Hub, GuardDuty

------------  
### Day 49

**CloudInfra:**
  - Integrated the serverless app with SQS and S3
  - Started automating Lambdas with CloudFormation
  - Watched a workshop on better IAM policy development 

------------  
### Day 50

**Started learning about ElectronJs applications**

------------  
### Day 51

**Spent some time playing around with Docker. Creating multiple containers with compose and assigning subnets.**

------------  
### Day 52

**Docker compose for creating multiple images**

------------  
### Day 53

**CloudInfra:**
  - Built a few custom docker images I use to run my python applications.
  - Watched a talk on Docker security best practices 
  - Looked into the docker-bench security audit container 

------------  
### Day 54

**CloudInfra:**
  - Learnt about Docker Engine API 

------------  
### Day 55

**CloudInfra:**
  - Finetuning IAM policies for lambda execution for users
  - Invoking Lambdas through CLI  

------------  
### Day 56

**CloudInfra:**
  - Most common AWS misconfigurations  

------------  
### Day 57

**CloudInfra:**
  - AWS automation with CLI 

------------  
### Day 58

**CloudInfra:**
  - DNS in detail - iterative resolvers, nameservers

------------  
### Day 59

**CloudInfra:**
  - Better AWS security - IAM checks for user roles/policies/inline

------------  
### Day 60

**CloudInfra:**
  - Designing scalabale AWS solutions + studying for certs

