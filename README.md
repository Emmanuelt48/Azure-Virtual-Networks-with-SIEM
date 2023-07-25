# Deploying Microsoft Sentinel SIEM in Azure Virtual Networks | Microsoft Azure
This Demo presents a virtual network implementation within the Microsoft Azure cloud environment and its integration with Microsoft Sentinel as SIEM solution. The Virtual network consists of virtual machines, load balancers, and an application gateway that also acts as a web application firewall (WAF). This WAF scans Internet traffic and provides centralized protection of web applications running in cloud environment from common exploits and vulnerabilities. Microsoft Sentinel as SIEM system automate visibility and incident response for cloud resources by collecting all the security information and events in both cloud and on-premises environments.
# Deployment
The project was realized in azure public cloud enviromnent. The virtual server used in this project were running Windows OS, Rule Querry was written using Kusto querry Language (kQL) and the code source in this repo are presented in JSON format. The code can be customized to meet individual requirements.
Main Points:  
	*Deployement of Virtual Network, it’s elements and security configurations.
  *Deployment of Microsoft Sentinel & log Analytics workbook.
  *Collecting logs from cloud instances and on-premises.
  *Configuragation of Analytics rules for Threat Monitoring and Detection.
  *Investigation of critical incidents.
	*Evaluation of Industry standards and regulation Compliance in Azure environment. 






