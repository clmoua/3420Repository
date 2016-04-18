#DFD Dictionary

##External Entities 

Corporate Developer: This individual in the organization is responsible for scanning the files for license, CVE, as well as CPE values and using it to manage the open-source code. 

Corporate Manager: This individual in the organization is responsible for storing and retreiving code information in the database.

National Vulnerability Database: Database that contains known vulnerabilities in open-source software.

CVE Database: Database that contains CVE information.


##Data Flows

File: Documents with necessary information needed.

Package: Group of documents or files in the system.

License Info: License information from open-source software.

CPE Information: NIST information with vulnerability.

CVE Information: List of vulnerabilities and exposures.

Policy Information: Information of context, threshold, and response to corporate manager.

Package Query:




##Data Stores

Risk DB: Database that has the risks involved with the open-source code.

NIST CPE Information: Database that has known vulnerabilities from NIST.

Policy Databse: Database that contains policy information.

##Processes

License Scanner: Scans to get license information.

Manage Code Streams: Manages incoming code.

Manage CVE Information: Manages incoming CVE information.


