try this 
https://github.com/jefferywmoore/CISSP-Study-Resources 
 
# CISSP
## Domain 1 
### 1.1 Code of Ethics 
* ISC^2 code of ethics 
  * Preamble 
  * Canons (4)
  * Complaints/ Violation 
* Organization Code of Ethics 
* Ethics & the internet RFC 1087 [IAB]
* Ten Commandment of computer ethics
* Code of fair information practices (5)
* Cybersecurity credentials collaborative C3
  * Integrity, objectivity, profissional, confidentiality.
### 1.2 CIA
* Confidentiality
  * &
  * Concealment 
  * Seclusion: storing in an out of the way location.
  * Isolation: Seperate from others.   
* Integrity
  * &
  * Oversight: an unintentional failure to notice or do something
  * Ineptitude: lack of skill or ability
* Availability
  * Depend on both of integrity & Encryption  
* Other security concepets 
  * Overprotection
    *   Overprotecting integrity can result in a restriction of availability.
    *   Over providing availability can result in loss of confidentiality and integrity.  
  * Authenticity: originates from its alleged source (the recipient can have a high level of confidance that the data is from whom it claims it be from)
  * Nonrepudiation: Digital Certificates, Session identifiers, transaction logs
  * AAA Service abbreviation refer to Authentication, Authorization, Accounting but it actually means the five elements: 
    * Identification: claming the be an identity.
    * Authentication: prove the identity (Identification and Authentication are single two steps process ) [passwords are the least secure].
    * Authorization: permission
    * Auditing: recording logs 
    * Accounting: review logs to check for compliance and violations
* Protection Mechanisms 
  * Defense in Depth:
    * a single failed control should not result in exposure of the system or data 
    * Serial configuration (oppsite that applicaiton new ideas)  
      * If parallel a threat could pass through a single checkpoint that did not address its particular malcious activity 
      * serial is very narrow but very deep, parallel is very wide but very shallow   
  * Abstraction: is used for efficiency, Similar elements are put into groups,classes, roles.(abstraction simplifes security).
    * thats is how to send input and receive output.

  * Data Hiding: subject cant see or access the data (not accesible)
    * Preventing application access hardware directly 
    * Insure that data existing at one level of security is not visble to process running at diffrent security level.
    * Data hiding is the act of intentionally positioning data so that it is not viewable or accessible to an unauthorized subject.   
  * Security through obscurity: hoping that no one will discover the issue and exploit it.
  * Encryption : :D

* Security Boundaries: is the line of intersection between two areas, high security and a low security one.
  * the distinction between classification is a security boundary.
  * in most casses interface is clearly marked, and unauthorized subject are informed that attempts to gain access will result in prosecution.
  * Logical: the points where electronic comminications a interface with device or service compay is legally responsible. ??xx?? 
  * Phycial: warning signs are posted .
  * security mechanisim must be reasonable, cost-effective and effcient (must be weighted agnist the value of the objects)
### 1.3 Evaludate and apply security Governance Principles 
 Preformed by Bard of director or CEO or CISO
 Security governance seeks to compare the security processes and infrastructure used within the orgnization
* Thrid-Party Governance: External Auditer (full and open document exchange).
* Document Review : 
  * Reading the exchanged materials and verifying them aginst standards and expectations 
  * if exchanged documents sufficient and meets the expectations or at least the requirements, then onsite review will be focised on compiance 
  * if exchanged documents is incomplete, inacurate or insufficient, the on site review is postponded until document is ready.
  * can result of voiding authorization to operate ATO
  * complete document can provide temporary ATO TATO.
* Manage The Security Function
  *  operating a business that focuses on the tasks of evaluating and improving security over time.
  *  preforming risks assessment to drive the security policy is the clearest and most direct example if managment of security function 
  *  Security must be measureabl.
  *  tracking and assessing security metrics is part of effective security.
*  Alignment if Security Function to Business Strategy Goals, Mission, and Objectives 
   * security management planning ensure proper creation, implementation, enforcment.
   * middel management to flesh out the security policy into standred, baseline procedures 
   * the operational managers / security professionals must implement the configuration in the policy 
   * top down approcah , not bottom-uo approch
   * InfoSec team should be led by designated CISO report to (Senior Managment,CIO,CEO,or board of directors)
   * CISO, CISO's teams outside the hierarchical structure.
   * CIO ensure information is used effectivly to accomplish bussiness objective.
   * CTO ensure that equipment and software work properly to support the bussiness function.
   * You May Found under CISCO 
     * CSO:Chief Security officer : Physical security. 
     * ISO: Infomration security Officer  
* policy development team to educate senior managment .
* security managment planning team shoud develop 3 plans :
  * Stratigic Plan 
  * Tactial Plan 
  * Operational Plan  
* Organizational Processes
  * Aquisitions,Divestitures
  * Minimizing inherent threats.
  * products that have resilient security are more expensive.
  * when considering the cost of merger.acuisition importanat to consider total cost of ownership
  * external org is unable to manger their business in secure basis how they can provide reliable security to you ? 
  * evaluation 3rd party integration 
    * On site assessment
    * Document Exchange and Review
    * Process/Policy Review
    * Third Party Audit (American Institue of certified public Accountants AICPA) Unbaiased review of security, and (SOC reports (Service Organization Control))
  * New Service/Hardware should meet or exceed your current security posture  
  * Review SLA
  * When Service is being crafted SLR must be defined, SLR statment of expectation of service/ preforamce 
  * SLR is provided by customer/ client prior to the establishment of SLA
  * Two  Additional examples 
    * strong security goveranace (change control/ change managment )
    * data classification
* Organizational Roles and Responsibilites 
* Senior Manager: 
  * Responsbile for the security 
  * must sign off on all security policy 
  * is liable for success or failure 
* Security Professional: 
  * Other Names:
    * Security Professional
    * InfoSec Officer 
    * CIRET (Computer incident response team) 
  * functional responsbility for security.
  * writing security policy and implementing it 
  * it maybe Operation but focus on protection more than function 
  * this role is often filled by team responsbile for designing and implementing security solutions.
  * security profissional and not decision makers 
* Asset Owner 
  * assgined to the person who classify information for placment onf protection ??xx??
  * responsbile for asset protection 
  * actual data managment tasks deligated to a custodian
* Custodian
  * responsbile for the tasks of implementing the protection 
    * Testing Backup
    * Validate data integrity 
    * Deploying security solution 
    * manage data storage
* User 
  * any person who access the secured system to work on tasks (least privilege)   
* Audtior 
  * reviewing and verifying that security policy is properly implemented 

### Security Control Frameworks 
* CBOIT (mapping of IT Security ideals to business objectives)
  * provide stakeholder value 
  * holistic approch 
  * dynamic gvernance 
  * governance distinct 
  * tailored to enterprise needs 
  * end- to end governance
* NIST 800-53 Rev.5 (general recommendation for orgnaizational security)
* CIS  (Provide Hardwawre, security configuration guides)
* NISK RMF (Establishes Mandatory requirments for deferal agencies)
  * Categorize, Select, Implement, Assess, Authorize, Monitor
* NIST Cyber Security (CSF)(on an ongoing basis for the support and imporovment of security over time )
  * Identify, Protect, Detect, Respond, Recover
* ISO (basis of implementing organization security and realted management)  
  * Plan, Do, Check Act
* ITIL (IT to Support bussiness growth)

