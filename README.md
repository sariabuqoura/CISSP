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
 security governance seeks to compare the security orocesses and infrastructure used within the organization with the knowledge and insight from external source 
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
* &
  * PCI DSS (Payment card Industry Data Security Standard)
  * OCTAVE self directed Risk Managment (Operationally Critical Threat, Assets, Vulneabilitiy Evaluation)
  * COSO (Commitee of sponsoring Organization) (Goals of the entire Organization) 
  * FARP (Faciliated Risk Anaylsis) (roundabletable brianstorm internal)
### Due care/due diligence
* Due care
  * Is doing the right action at the right time 
  * Is Practicing the indiviual activites.
* Due diligence
  * Is establishing a plan, policy, and process to protect the interests of the organization.
  * often involves gathering information through discovery, risk assessments and review of existing documentation; developing a formalized security structure
  * Is Knowing what should be done and planning for it 
* Showing both is the only way to diprove negligence.
### Security Policy, Standards, Procedures, And Guidenlines 
Developing and implementing documented security policy, standard, procedures, and guideline produces a solid and reliable security infrastructure
Once the security policy documentation is reasonably complet, it can be used to guide decisions
* Policy
  * Mandatory
  * Define the scope of security needed by the organization. 
  * Dicusess the assets that require protection. 
  * extend which securitu solition should go to provide the protection. 
  * Define strategic security objective,Vision, and goals.
  * Outline security framework.
  * indicate compliance requirments. 
  * define acceptable risk level. 
  * "This document is often used as the prrof that senior managemenet has exercised due diligence".
  * "Acceptable user Policy: define a level of acceptable perforamnce and expectiaon of behavior and activity".
  * fewer document because they contain in general broad discussions of overview and goals. 
* Standards
  * Mandatory 
  * define compulsory requirements for the homogenous use of hardware, software, technology, and security controls. 
* Baseline
  * Mandatory
  * Define Minimum level of security that every system throughout 
  * base line more operationally 
  * all systems not complying with the baseline should be taken out of production
* Guidelines
  * Not Mandatory
  * Offer recommendation on how standards and baseline are implemented
  * Guidelines are flexbile 
* Procedures
  * Mandatory
  * Is Detailed,setp by step how-to document.
  * Purpose of procedure is to ensure the integrity of business process 
  * Contanis details rather than policy for the below :
    * Not all users need to know the security standards,baseline,guidelines, and procedure
    * it is easier to update   
### Threat Modeling
 * is a process where potential threats are identified, categorized, and analyzed.
 * proactive measure during the design or development
 * reactive once a product has been deployed 
 * checks :
   * identifes the potential harm
   * probability of accurence
   * priority of concerns 
   * means to readicate or reduce the threat. 
 * microsoft moto : Secure by desgin, secure by default, secure in development 
   * has goals of 
     * to reduce the number of security related desgin and coding defects 
     * to reduce to severity of any remaning defects 
* Defensive approach
  * during the initial desgin, based on prediciting threat and designing in specific defense during the coding and crafting process 
  * Integrated security solutions are more cost effective and more successfull than those shoehorned in later {proactive approach to threat management}
  * Not all threats can be predicted during the desgin phase so reactive approach to threat managment is still needed.(threat hunting or adversarial approach).
  * (threat hunting or adversarial approach), after deployment could be in test or lab or general marketplace
    * Core concept behind echical hacking, pentesting, source code review, and fuzzing.
    * result in addtional effort in coding to add new countermeasure released as patching.
      * this result in less effective security improvements.
* Identifying threats:
  * The ultimate goal is to prioritize the potential threats.
  * Structured approach 
    * Focused on assets: assets evaluation, and threats to the valuble assets.
    * Focused on attackers : attacker motiviation goals, or Tactics techniques and procedures (TTPs)
    * Focused on softwares: Company create softwares  
  * Microsoft approach (STRIDE)
    * Spoofing : bypass filters 
    * Tampering : change data 
    * Repudiation : deny action
    * Information disclosure : distribution of private confidential to external or unauthorized entities 
    * Denial of service : prevent authorized use of a resource 
    * Elevation of privilege : change to account with greater privilege
  * Process for attack simulation and threat analysis PASTA
    * Risk- centric 
    * aims to select or develop countermeasures in relation to the value of the assets to be protected.
    * steps 
      *  Stage I: Definition of the Objectives (DO) for the Analysis of Risk.
      * Stage II: Definition of the Technical Scope (DTS)
      * Stage III: Application Decomposition and Analysis (ADA)
      * Stage IV: Threat Analysis (TA)
      * Stage V: Weakness and Vulnerability Analysis (WVA)
      * Stage VI: Attack Modeling and Simulation (AMS)
      * Stage VII: Risk Analysis and Management (RAM)
    *  Visual, Agile, and Simple Threat (VAST) is a threat modeling concept that integrates threat and risk management into an Agile programming environment on a scalable basis
    *  consider threat level from indivduals including employees adversaries and treust pratners.
    *  Compny faces threats from nature, technology, people, always consider the best and worst possbile outcomes.
* Determining and Digramming Potential attacks
  * creating digram of the element involved in transaction along with indication of data flow and privilege.
* Preforming Reduction anaylsis 
  * Decomposing the application 
  * purpose is to gain a greater understandign of the logic of the product, its internal components, as well as its interncation with external elements.
    * Trust boundries: level of trust 
    * Dataflow Paths: the data movement 
    * Input points : location where external inout is received 
    * Privileged Operations : any activity require greater privilegs 
    * Details about security stance and approach : the declaration of security policy,foundation, assumptions 
    * once the threats are identified should be fully documeneted by target, consequences of a threat.
* Prioritization and Response 
  * Ranking & Rating 
  * Probility * Damage Potential Ranking 
  * High/Medium/Low 
  * DREAD System
    * Answer five questions  
      * Damage potential: how server is the damage 
      * Reproducibilility: how complicated to reproduce the exploit 
      * Exploitability : how hard to preform the attack
      * Affected Users : how many users are likley to be effected 
      * Discoverability : how hard for attacker to find it out 
    * Responses are needed for there threats 
    * remidate threats should be considered and weighted according to their cost and effectivness
    * threat modeling is similar to the risk assessment 
      * Threat modeling focus on the attack it self
      * Risk assessment focus on the asset. 
### Supply chain risk Managemen
* Hardware, devices, network, cloud services are not built by a single entity 
* vendor are perform the final assembly 
* any finished system has a long and complex history known as its called supply chain.
* SCRM is the means to ensure that all of the vendors or link in the supllu chain are reliable .
* each link in the chain should be responsbile and accountable to the next link 
* Goals 
  * ensure that the finished product is of sufficient qulity
  * no point in the process was any elemnt counterfeteited or subject to unauthorized or malicious mainuplation or sabotage 
* another threat vector 
* Just-in-time supply chain 
* is there surplus or Buffer of materials 
* attack on supply chain could result in flawed or less reliable products 
* supply chain attack present a risk that can be challenging to address 
* it may nearly impossbile to discover an extra chip placed on a device mainboard or change in firmware.
* ongoing security monitoring managment and assessement maybe be required, this maybe made by the end-of-chain organization or external auditor 
* if org is unable to manage thier own operation on as secure basis, how can they protect you ? 
* software, hardware myst meet ot exceed in the final product
### Laws 1
 * Criminal
 * Civil Law
 * Administrative Law
### Laws 2
 * Computer Crime 
   * Comprehensive crime contract control act 1984 
     * First time to cover computer crime in law.
   * Computer Fraud and abuse Act 1986 
     * Unthorized access or in excess of authorized privileges (classified infomration or financial in fedral law)
     * Unthorized access used by federal goverment
     * User federal computer to commit a fraud
     * Case malicious damage to federal computer excess of 1000 $
     * modify medical records 
     * traffic in computer password interstate commerce or federal computer system
     * && Congress addedd the below 
       * any computer used exclusively be the US goverment 
       * by financial inistitution
       * any computer used by the goverment or finincial when the offense impedes the ability of the goverment or institution to use that system
       * any combination of cupters use to commit an offense when they not all located in same state  
   * Computer Fraud and abuse Act Amendments 1994 (big change on internet )
     *   outlawed the creation of any malicious code that may case damage 
     *   covers any computers used in interstate commerce not only federal 
     *   allowed imprisonment
     *   pursue civil action 
   * National Information Infrastructure protection act 1996
   Congress passed another set of amendments covers new area 
     * CCFA to cover computers used in internationla commerce . 
     * extends similar protections as railroads , gas piplines , electric power grids , telecommunication 
     * treats any interntional or reckless act that causes damage as felony 
   * Federal Sentencing Gudelines 1991
     * Provided punishment guidelines to help federal judges to interpret computer crime law.
     * formalize prudent person rule, senior executives to take personal responsbility.
     * allowed org and exectives to minimize punishment (if due diligence were practised )
     * guiglines outlined three burdens of proof for negligence 
       * person accused of negligence must have a legally recognized obligation. 
       * person must have faild to comply with recognized standards. 
       * must be causal relationship between the act of negligence and subsequant damage.
   * Federal Information Security Managment Act (FISMA) 2002
     * require that federal agencies implment an information security program
     * require that goverment agencies include the activites of contractors in their security managment 
     * FISMA replaced Two laws (Computer Security Act of 1987 and Government information security reform act of 200)
     * FISMA outline the elements of the below 
       * periodic assessment of risk 
       * policy and procedures that are based on risk assessment, cost effectivly reducing the infomration security to acceptable risk
       * subordinate plan for providing adequate information security for network, facilities, information system. 
       * security awareness tranning 
       * periodic testing and evaluation 
       * process for planning, implmenting,evaluating, documenting remedial action to address ny deficiencies in the infomraiton security policy,proc,practices 
       * procedures for detecting, reporting, and repsones, to security incidents 
       * plans and procedures to ensure continnuity of operation.
   * Federal Cybersecurity Laws 2014
     * centralizing federal cycbersecurity responsibility with department of home land security 
       * defnese realted to cyber security issues remain the responsbibility of the secretary of defense and the director of national inteleigence bears bears responsbility for intelligence-related issues 
       * charge NIST with to work on voluntary standards
       * notional cybersecurity protection act (charge home land security to establish cybersecurity center)
         * the goal is to server the interface between fedral and civilian for sharing cybersecurity risks, incidents, analysis, warnings 

### Intellectual Property (IP)
 * Copyright 
   * Unauthorized duplication of their work 
   *  protect the source code, it doesnt protect the idea or process behind the software.
   *  granted automaticly for 70 years.
   *  if it was for hire it is protected for 95 from first publish or 120 year from create or whos shorter.
   *  Digital Millennium Copyright DMCA
      * Compliance with World intellectual Property Organization WIPO
      * prohibtion of atempts to circumvent (disable) copyright mechanisms placed on protected work.
        * up to 1 million and 10 years in prison, Nonprofit and libraries and schnool are exempted from this provision.   
      * prohibtion of creation of backup copies, maintenance, testing, or routine used unless the software is licensed for user and must comply with license agremment
      * streaming video and audio is treated as eligible nonsubscription transmissions
      * limit the liability for ISP when their circyits are used by criminals violating the copyright law 
      * ISP must meet the below 
        * the transmission must be initaiated by person not the provider 
        * the transmission routing, provision of connections or copying must be carried out by an automated technical process without selection 
        * the service provide must not determine the recipients of the material 
        * any intermediate copies must not ordinarily accessible to anyone other than anticipated recipients, and must be retained for longer than reasonably necessary
        * the material must be transmistted without any modification
        * exempts the actives of ISP for caching, search engine, and storage of infomration on a network by individual users, ISP must take action to remove the materials unon notification of the infringement. 
     
 * Trademark
   * protect creative works, which is (words, slogans, logos used to identify a company )
   * avoid confusion in the market 
   * do not need to be offcially registered
   * (TM) means you intend to protect.
   * (R) after registration and it may take more than 1 year with attorny to perform a due diligence 
   * one advantage of trademark registration is that you may reguster a trade you intend to use but no necessarily already using. (intent to use)
   * if you dont register with PTO your protection begines only when you first use the trademark 
   * granted for initial period of 10 years, can can be renewed for 10 years .
   * accpetance of trademark 
     * must be be conusingly similar to another trademark
     * shouldnt be descriptive of the goods and services  
 * Patnets 
   * Desgin patents protect the appearance (weak IP)
   * Utility patents protect the function  
   * protect the intellectual property of the inventors.
   * provide period of 20 years, from the time of invention
   * at the end of patent exclusivity period, the invention is in the public use.
   * invention must be 
     * invention must be New 
     * invenction must be useful
     * invention must not be abvious, (cup to collect rain water) 
   * patent trolls.
 * Trade secerts
   * coca-cola KFC ,sercet blend of herbs and spices 
     * why not copyright ot patenet cover it 
       * filing a copyright or patene application require that you publiclt disclose the details of your work 
       * copyrigh and patenets both provide protection for a limited period of time , then other firms are free to use it. 
     * no need for registration 
     * you must implement adequate controls within your org to ensure that only authorized personnel with ta need to know the secert have acces to them 
     * you must take stps to demonstrate that you value and protect your intellectual property, failure to do so may result in loss of trade secret protection 
     * trade secrets protection is one the best way to protect computer software (it keeps it out of the hands of your competitors in the first place ) 
       * patenet law does not provide adequate protection for computer software products 
       * copyright law protects only the actual text of the source code. dosent prohibit other from rewriting your code in diffrent form 
     * economic espionage act of 1996
       * fine 500,00 and imprisoned for 15 years for US coropration
       * fine 250,00 and impriosned for up to 10 years for other circumstances .  
 * Licensing
   * Four Types 
     * Contractual: written contract (high-priced, high specialized)
     * Shrink-Wrap: agreement written on the outside of the software (once its opened its activated)
     * Click-Through: click on licesning button 
     * Cloud Service : it provide link to lefal terms and checkbos for user to confirm that they read and agree 
   * Import/Export 
     * export of senstive hardware and software products to other nations 
     * Internernational traffic in arms regulations(ITAR)
       * controls the export items are specifically designed as military and defense items on (USML US Munitioons list ) list   
     * the export administration regulation (EAR) 
       * cover a broader set of items that are designed for commercial use but have military applications on (CCL commerce control list) list 
   * Countries of concern
     * Bureau of industry and security  
   * encryption export controls 
     *  it was virtually impossible to export even low grade encryption, this placed US software manufactures at a great competitive disadvantage, to foreign firms that faced no similar requlations.
     *  presidant directed the commerce department to revise this regulation . 
     *  current regulation now designate the categories of retail and mass market security software, the rule now permit firm to submit these products for review by the commerce department in 30 days 
   * Privacy 
     * US Privacy Law   
       * Fourth amendment 
         * the right for people to be secure by their person, houses,papers,and effects, against unreasonable searches and seizures, shall not be violated.
         * if upon probable case supported by oath or affirmation, particularly describing the place to be search and the persons and the things to be seized.
         * the court have expanded their interperation for the foruth amendment to inlcude the protection aginst wiretapping and other invasions of privacy. 
       * Privacy Act of 1974 
         * Only applies for government agencies. 
         * limits the ability of fedral goverment agencies to disclose private information to other people or aginces without prior written consent .
         * expection for law enforcement
         * only maintain records that are necessary for conducting their business, and distory those records when they are no longer needed 
         * provide formal procedure for individuals to gain access to records the goverments maintanis about them and amend the wrong.   
       * Electrnoic Communications Privacy Act of (ECPA)1986
         * it makes crime to invade the electronic privacy of an individual.
         * federal wiretap (data traveling via a physical wire )
         * Prohibit
           * apply to illegal any interception if electronic communications.
           * or to the intentional, unauthorized access of electronically stored data.
           * and defines those situations in which disclosure is legal.
           * it protects against the monitoring of email and voicemail 
           * prevent provider of those services from making unauthorized disclousres of their content.
           * it makes it illegal to monitor mobile elephone conversations (fine 500 and prison up to 5 years) 
       * Communication Assistance for Law Enforcments Act (CALEA) 1994
         * Amend the ECPA 1986 to require all communications carriers to make wiretaps possbile for law enforcements with court order regadless on the technology. 
       * Economic Espionage Act of 1996
         * extened the definition of property to include proprietary economic information so that theft is no longer physical constraints. 
       * Health Insurance Protability and Accountability of (HIPAA)1996
         * Strict security measures for hospitals, physicians, insurance, and other organization that process or store private medical infomraiton. 
         * Defines the right of individuals who are the subject of medical records and requires org that maintain such records to disclose these rights in writing.
       * Health information technology for economic and clinical health act of (HITECH) 2009
         * added new way to treat business associates law 
           * Covered entity :  Covered Entities* have direct contact with patients
             * Doctors, Clinics, psychologists, Dentists, Chiropractors, Nursing Homes, Pharmacies.
           * Business accociates :Business Associates don’t see patients, but they maintain or have access to Protected Health Information (PHI). 
             * Collections agency,Billing or coding company,IT consultant,Law office or accounting firm,Subcontractor providing remote backup services 
         * any relation between Covered entity and Business accociates must be governed by written contract known as (business associate agrement BAA)
           *  Covered entity and Business accociates are subject directly to HIPAA
         * introduced new data breach notification requirements.(if breach exceed 500 )
            * must notify effect individual of the breach 
            * notify secretary if health 
            * notify human service 
            * media    
       * Children Online Privacy Protection act  (COPPA )of 1998
         * Demand websites that cater to children or collect from children
           * website must have privacy notice that clearly states the types of infomration they collect and what is used for 
           * website must have privacy notice that clearly states the types of infomration they used for
           * what type of data disclosed to 3rd party 
           * contact infomraiton for the oprator site 
         * Parents must be provided with the opportunity to review any information collected from their children, and permanently delete them.  
         * Paretn must give verifiable consent to the collected infomraton about younrer than age of 13,
           * exceptions in the law allow website to collect minimal information solely for purpose of obtanining such parental consent.  
       * Gramm-leach-Blily Act (GLBA) of 1999
         * there was stric govermental barriers between finnanical instituions.(banks, insurance, credit provider )
           * limited services 
           * limited shared infomation 
           * GLBA relaxed the regulations concerning ther services for each inistiuation 
             * this lead to far-reaching privacy implications,so 
               * it inculded limitation on type of exchanged infomartion even subsidaries 
               * required financial instituation to provide writeen privacy polices to all their customers     
       * USA Patriot act of 2001
         * Tools required to intercept and obstruct terrorism (monitoring electronic communications)
         * changed how govermental obtin  wiretapping authorization.
           * police were obtin warrants for only one circuit at a time 
           * single circuit at a time modified to the below 
           * allow authorities to obtin a blanket authorization for a person and moniter all communications . 
         * they way they deal with ISP, which ISP may voluntarily provide the gov with large range of infomration.
         * allows the gov to obtain detailed infomation on user activity through the user of subpoena (as opposed to a wiretap) 
         * amends CFAA to provide more sever penalties for criminal acts (... jail for 20 years )
         * till now not renewed 
       * Family Educational Right and privacy act (FERPA).
         * effect any educational inistitution that accpet any form of funding from federal government. 
         * it grants certain privacy right to student older than 18 and the parents of minor student.
         * it includes 
           * parents/students have the right to inspect any eductional records 
           * parents/students have the right to request correction of records and include statments sontesting anything not correct 
           * schools may not rlease personal information from student records without written consent, except under certain circumstances 
       * Identify theft and Assumption Deterence act 1998
         *  before 1998 only creditors (Banks) were the legal victoms 
         *  after the act creditor and person were the legal victams 
         *  also adding person for 15 years and fine 250,000 for who found guilty 
     * European Union Privacy Law
       * Apply for all individually Identifiable inforamtion ,not like US for spesific industries or categories of information. 
      * European Union Data Protection Directive (DPD) (1995)
        *Processing of data require to meet one of the below  :
         * Consent
         * Contract 
         * Legal Obligation
         * Vital interest of data subject
         * blanace between the interest of data holder and the interests of data subject.
        * outlined key right for individual
          * right to access the data
          * right to know the data source
          * right to correct inaccurate data
          * right to withhold consent to process data in some situations 
          * right of legal action should these rights be violated 
        * forced all organiazation even outside the Europe to consider the privacy obligation due to transborder data flow requirmetns 
          * in case citizenes left the EU theose sending the data were requied to ensure that it remaind protected.         
      * European Union General Data Protection Regulation (2016)
        * main purpose to provide single harmonized law that cover data thoughout EU.
        * apply for who process EU residents infomraiton 
          * lawfulness, fairness and transperancy : you must not process data in a manner that is misleading ,you must be open and host about data processing acvtivity
          * purpose limitation: cleary document and disclose the purpose for collecting and limit it to this purpose 
          * Data minization: data you process is adequate and limited 
          * accuracy: data you collect create or maintain is correct. 
          * storage limitaion : right to be forgotten : right to delete the data .
          * security :must have appropriate integrity and confidentiality
          * Accountability: must be responsbile for the security and demonstrate your compliance.
      * Cross Border Infomration sharing 
     * Canadian Privacy Law  

