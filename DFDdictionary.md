#DFD Dictionary

##External Entities 

**Corporate Developer:** This individual in the organization is responsible for scanning the files for license, CVE, as well as CPE values and using it to manage the open-source code. 

**Corporate Manager:** This individual in the organization is responsible for storing and retreiving code information in the database.

**National Vulnerability Database:** Database that contains known vulnerabilities in open-source software.

**CVE Database:** Database that contains CVE information.

##Data Flows

**File:** Documents with necessary information needed.

**File/Package:** File or package.

**Package and CPE Information:** Contains both package and CPE information.

**CPE and CVE Information:** Contains both CPE and CVE information.

**CPE Request:** Request from NIST Database.

**CPE Response:** Response from NIST Database.

**CVE Response:** Response from CVE Database.

**CVE Request:** Request from CVE Database.

**Project Info Request:** Request from manager about project.

**Project Info Response:** Response from manager about project.

**Policy Response:** Policy response from Policy Database.

**Package and CPE Information:** Contains both package and cpe information.

**Package:** Group of documents or files in the system.

**License Info:** License information from open-source software.

**CPE Information:** NIST information with vulnerability.

**CVE Information:** List of vulnerabilities and exposures.

**Policy Information:** Information that contains context, threshold, and response to corporate manager.

**Package Query:** NIST request for package to be scanned.

##Data Stores

**Risk DB:** Database that has the risks involved with the open-source code.

**NIST CPE Information:** Database that has known vulnerabilities from NIST.

**Policy Databse:** Database that contains policy information.

##Processes

**License Scanner:** Scans to get license information.

**Manage Code Streams:** Manages incoming code.

**Manage CVE Information:** Manages incoming CVE information.


