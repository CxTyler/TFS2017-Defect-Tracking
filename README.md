# TFS2017-Defect-Tracking

## Integration with Checkmarx SAST Results
### 1.	Generate CxSAST XML Results (Post-Scan Action or Manually Generated)
### 2.	Setup Custom Fields within Azure DevOps (formally VSTS) or TFS (Team Foundation Server)
####  a.	Similarity ID - a Checkmarx specific field to identify a unique Vulnerability
####  b.	Node ID - a Checkmarx specific field to identify a unique node for each Result
### 3.	Create Customer Script to parse the XML report for relevant issue tracking data
####  a.	Vulnerability Name
####  b.	Source Filename
####  c.	Destination Filename
####  d.	Assignee
####  e.	Severity
####  f.	Priority
####  g.	Deep link
### 4.	Incorporate Work Items into the Custom Script. Create Work Items via Microsoft APIs - REST APIs for both Azure DevOps and TFS (2015,2017,2018) are available to create/update/delete Work Items
####  a.	API Versions Support
#####   i.	REST API Versioning - https://docs.microsoft.com/en-us/azure/devops/integrate/concepts/rest-api-versioning?view=vsts
#####   ii.	TFS REST API Overview - https://docs.microsoft.com/en-us/azure/devops/integrate/concepts/rest-api-versioning?view=vsts
####  b.	API Documentation
#####   i.	Azure DevOps Work Items - https://docs.microsoft.com/en-us/rest/api/azure/devops/wit/?view=azure-devops-rest-4.1
#####   ii.	TFS Work Items -https://docs.microsoft.com/en-us/azure/devops/integrate/previous-apis/wit/work-items?view=tfs-2017


Exhibit A – TFS2017 Python Script
Exhibit B – WebGoat .NET CxSAST XML Report




