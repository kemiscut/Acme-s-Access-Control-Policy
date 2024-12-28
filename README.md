# Acme-s-Access-Control-Policy

CLASSIFICATION |	REF	                  | VERSION	| DATE	       | OWNER	                    | AUTHOR
|---------------|-----------------------|----------|-------------|----------------------------|--------|
INTERNAL	      |ACME-ISMS-POL-OO2-ACP |	0.1	    | 22 DEC. 2024 |Acme Financial Institution	|Aishat Alli

### CONTROL OF DOCUMENT
### REVISION HISTORY
VERSION	| DATE	       | REVISION AUTHORS	| SUMMARY OF CHANGES
|-------|------------- |-------------------|-------------------|
0.1     |22 DEC. 2024  |	AISHAT ALLI	    |First draft of the Access Control Policy based on ISO 27001, NIST 800-171, PCI DSS and GDPR
0.3			|              |                   
0.5		   

### APPROVAL
NAME	| TITLE	| STATUS
|-----|--------|------|

### 1.	Introduction

In an era defined by rapid digital transformation and an increasing reliance on technology, safeguarding sensitive information has become paramount. Access to this information must be carefully managed to mitigate risks. 
This policy is created to address the critical need for effective identity and access management, providing a robust framework that aligns with international standards such as ISO/IEC 27001:2022,  the General Data Protection Regulation (GDPR), the Payment Card Industry Data Security Standard (PCIDSS), and the National Institute of Standards and Technology (NIST) guidelines for access control.

2.0 PURPOSE
The purpose of this policy is to establish a framework for access control that ensures the protection of sensitive information and information processing facilities in alignment with Acme’s business requirement.

### 3.0 OBJECTIVES
The primary objectives of this policy are to:
- Limit access to information and information processing facilities
- Ensure authorized user access and to prevent unauthorized access to systems and services.
- Ensure users are accountable for safeguarding their authentication information.
- Prevent unauthorized access to systems and applications



### 4.0 SCOPE
This policy applies to all Acme’s assets including but not limited to information systems, data, processes, business technologies, employees, contractors, third-party service providers, etc.

### 5.0 RELATED DOCUMENTS
Information classification policy
Information handling policy
Asset management policy

### 6.0 GLOSSARY

### 7.0 ROLES AND RESPONSIBILITIES
#### 7.1  Top Management Responsibilities
Acme top management shall provide necessary resources and support to implement and enforce this access control policy. 
Acme top management shall ensure that security awareness training is provided to all personnel and that access control measures are regularly reviewed and updated.

#### 7.2  Information Technology (IT) Responsibilities
IT team shall:
Ensure that users are provided with access to the network and network services that they have been specifically authorized to use by the asset owner.
Implement measures to restrict and control the allocation and use of privileged access rights.
Configure and maintain access controls on information systems, provision and deprovision all employees and external party users  accounts promptly based on documented access requests and approvals. 
Manage access rights, permissions, and authorizations for users based on their job functions, following standard security principles such as the principle of least privilege, need-to-know, need-to-use, etc.
Remove or suspend the access rights of an individual to information and assets associated with information processing facilities and services upon termination.

#### 7.3  IT Security Responsibilities
The IT Security representative shall:
- Establish, document and review the access control policy based on business and information security requirements.
- Oversee the implementation and enforcement of access controls across Acme.
- Conduct regular risk assessments to identify vulnerabilities and threats related to access controls.
- Provide guidance and training to staff regarding access control best practices.



#### 7.4 Human Resources Responsibilities
The HR team shall:
- Ensure that a formal user registration and de-registration process is implemented to enable assignment of access rights by the IT team.
- Provide timely information to IT and security teams regarding new hires, transfers, and departures to ensure accurate provisioning and de-provisioning of access.
- Ensure the return of access credentials and assets from departing employees and contractors.
- Communicate and enforce HR policies related to access control, confidentiality, and data protection during the employment lifecycle.
#### 7.5 Asset Owners Responsibilities
Assets owners shall:
- Determine appropriate access control rules, access rights and restrictions for specific user roles towards their assets.
- Define access requirements and specify authorized users or groups
- Collaborate with IT and Security teams to ensure access rights align with Acme policies and regulations.
- Review and validate access rights to their assets every quarter or  if there is(are) immediate business need(s) such as resignation of a privileged user, access related security incidents, etc.
#### 7.6 Employees and Users Responsibilities
All employees and users who access Acme’s information and information systems shall:
- ensure to keep secret authentication information confidential, ensuring that it’s not divulged to any other parties, including people of authority. 
- avoid keeping a record (e.g. on paper, software file or hand-held device) of secret authentication information, unless this can be stored securely and the method of storing has been approved by Acme asset owners (e.g. password vault).
- ensure proper protection of passwords when passwords are used as secret authentication information in automated log-on procedures.
- change secret authentication information whenever there is any indication of its possible compromise.
- not use the same secret authentication information for business and non-business purposes.

### 8.0 POLICY STATEMENTS
#### 8.1  Access Control 
- The IT Security team shall ensure that the approved access control policy is known and communicated to all affected parties.
- The IT team shall limit access based on need to know and according to job responsibilities in order to ensure that critical data can only be accessed by authorized personnel.
- All implemented access control to information systems/assets shall follow the principle of implicit denial i.e Everything is generally forbidden unless expressly permitted.
- All relevant stakeholders (Asset owner, IT, etc) shall ensure that appropriate measures are in place to monitor accesses to assets.

#### 8.2 Access to network and network services
All individual non-console administrative access and all remote access to the IT environment shall be possible using multi-factor authentication. 

#### 8.3 User registration and de-registration
Asset owners shall implement appropriate technical and organizational measures to ensure and to be able to demonstrate that processes are performed in accordance with the GDPR Regulation. Those measures shall be reviewed and updated where necessary.
The IT team shall assign all users a unique user name before allowing them to access system components or IT environments. 
Where possible, other authentication mechanisms such as physical security tokens, smart cards, and certificates shall be assigned to an individual account, applications, service accounts, systems, etc.
Access to the types of transactions and functions that authorized users are permitted to execute shall be limited.
#### 8.4 Management of privileged access rights
- The IT team shall allocate privileged access to users on a need-to-use basis and on a case-by-case basis, i.e. based on the minimum requirement for their functional roles.
- The IT team shall establish an authorization process and maintain a record of all privileges allocated. Privileged access rights shall not be granted until the authorization process is complete.
- The use of group, shared, or generic IDs, or other authentication methods shall strictly be prohibited. 
- Service providers with access to customer environments shall use a unique authentication credential (such as a password/passphrase) for each customer environment with an extra layer of security such as MFA.

#### 8.5 Removal or adjustment of access rights
- The IT team shall remove the access rights of all employees and external party users to information and information processing facilities upon termination of their employment, contract or agreement, or adjusted upon change.
- Access must be authorized and based on individual job function; access must be revoked immediately upon termination, and all physical access mechanisms, such as keys, access cards, etc. shall be returned or disabled.

#### 8.6 Use of secret authentication
- Users shall be required to follow the organization’s practices in the use of secret authentication information.
- When passwords are used as secret authentication information, quality passwords with sufficient minimum length shall be selected which are:
easy to remember;
1. not based on anything somebody else could easily guess or obtain using person related information, e.g. names, telephone numbers and dates of birth etc.;
2. not vulnerable to dictionary attacks (i.e. do not consist of words included in dictionaries);
3. free of consecutive identical, all numeric or all-alphabetic characters;
4. if temporary, changed at the first log-on.

#### 8.7 Information access restriction
- Access to information and application system functions shall be restricted in accordance with the access control policy.
- The IT team shall establish an access control system(s) for system components that restricts access based on a user’s need to know, and is set to “deny all” unless specifically allowed.
- The IT Security team shall authorize the remote execution of privileged commands and remote access to security-relevant information.
#### 8.8 Secure log-on procedures
- Access to systems and applications shall be controlled by a secure log-on procedure.
- The procedure for logging into a system or application shall be designed to minimize the opportunity for unauthorized access. The log-on procedure shall therefore disclose the minimum of information about the system or application, in order to avoid providing an unauthorized user with any unnecessary assistance.
- Unsuccessful logon attempts shall be limited to 3 times. A User session shall be automatically terminated after a defined condition.


#### 8.9 Use of privileged utility programs
- The use of utility programs that might be capable of overriding system and application controls shall be restricted and tightly controlled.
- The IT and IT Security team shall limit the use of utility programs to the minimum practical number of trusted and authorized users. Identification, authentication and authorization procedures shall be used for utility programs.
- The IT and IT Security team shall control and verify connections to and use of external systems.

#### 8.10 Access control to program source code
- The IT Security team shall control access to program source code and associated items (such as designs, specifications, verification plans and validation plans) in order to prevent the introduction of unauthorized functionality and to avoid unintentional changes as well as to maintain the confidentiality of valuable intellectual property.
- If the program source code is intended to be published, additional controls to help get assurance on its integrity (e.g. digital signature) shall be considered.
- Accesses to source codes shall be controlled based on the developers job function. Standard developers shall not have the permission to push code to production.

### 9.0 Non-Conformity
All employees are subject to follow the requirements here described unless an exception is identified and required by the same regulatory bodies Acme GROUP is subject to. 
Any exception or deviation to the access control policy and supporting directives must be based upon a unique legislative or business requirements.
Requests for a policy exception shall be duly documented, related risk assessed and submitted to the Information Security representative before the waiver or exception may be implemented. 
All approved exceptions or deviations shall be recorded and managed in the risk register and reviewed on an annual basis.
