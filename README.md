# SMI Brazil Virtual Assistant

**[SMI Brazil Virtual Assistant](http://smi-brazil-assistant.w3ibm.mybluemix.net)** is a chatbot designed to assist the different support teams on how to interact with the SMI Enterprise Automation Solutions. 

The application provides essential information on how different the monitoring/automations are implemented on SMI's supported customers, and how to interacts with the different sources of information used by the SMI team.

**This chatbot is still in beta, and should not be considered ready for production.**

### Frameworks

This chatbot was developed using **Node.js** and hosted on Bluemix with a continuous delivery pipeline. The application also integrates with the **[IBM Watson Conversation API](https://www.ibm.com/watson/services/conversation/)**.

# Dialog Structure

This chatbot is designed to assist with the most common information and the most frequently asked questions. The idea is to provide guidance to the different support teams through the SMI supported clients documentations, especially for resources that are not familiar with SMI's official information repositories.

![SMI Virtual Assistant Dialog Diagram](https://github.com/IBM-SMI-Brazil/smi-brazil-assistant/blob/master/images/SMI%20Chat-Bot.png)


# Dialog Steps

To simplify the dialog we've decided to train the bot in following categories:

### 1. **Automation & Solutions**: 
This category is related to all solutions that were created to automate manual tasks, reduce repetitively efforts or waste reductions in general. We're also considering at this category the custom monitors and any other custom solution that is implemented at our supported customers.

#### Maintenance: 
Any automation, solution or script that is used for maintenance related tasks, for example: filesystem clean-up, directory/file permission fixer, and etc.

#### Reports:  
Any automation, script or solution that assists on displaying the different data/information required by the SMI Team or any other support teams. For example: Book of monitoring, health check reports, audit and problem reports, etc.

#### Custom Monitors:
This category should include any monitoring solution that is not part of the standard monitoring packages and/or any monitor created for a specific requirement of the supported customers, such as: A script created to monitor an appliance, a script that generates an error log based on a customer application, etc.

#### Custom Solutions:
Different from the custom monitors, this section should include any non-standard solution implemented by SMI Enterprise Automation team, which are not necessarily related to monitoring, such as custom ticketing or alerting tools,  recovery actions for other solutions, or even custom made solutions such as this Virtual Assistant.

####  Waste Reduction Automation:
Any solution that is being used as a way to avoid repetitive effort and reduce wastes, such as scripts used to automate the install and/or configuration of monitoring, and utilities that assist the Operators or SMI Analysts on interacting with the different systems on the environment.


###  2. **Boarding Procedures**: 
All procedures related to on-boarding or off-boarding resources. Such as mandatory training and certifications that are required to work on the supported customers, and also how to get access to the servers and supported tools.

### 3. **Contacts**
A list of all key contacts from all the supported accounts.

### 4. **Incident Management**
A guide to all process and policies related to Incident Management, and also any operational procedure related to how to handle incidents at the SMI supported customers.

### 5. **Change Management**
A guide to all process and policies related to Change Management, and also any operational procedure related to how to handle change tickets at the SMI supported customers.

### 6. **Operational Procedures**
All instructions and guides intended to document and assist the different support teams on performing their routine activities.



## Contact

In case you need any further information or assistance, the following folks can be contacted for assistance.

Team            |        Name   |    Email    | Role  
---------------------|------------------------------------|---------|------|
<img src="https://github.com/IBM-SMI-Brazil/smi-brazil-assistant/blob/master/images/gportog.png" width="120"> | [Gustavo Porto Guedes](https://www.linkedin.com/in/gustavo-porto-guedes/) | gportog@br.ibm.com | Developer
<img src="https://github.com/IBM-SMI-Brazil/smi-brazil-assistant/blob/master/images/hugocris.png" width="120"> | [Hugo Cristiano Lima](https://www.linkedin.com/in/hugo-cristiano-lima-dos-santos-b27609b6/) | hugocris@br.ibm.com | IT Specialist
<img src="https://github.com/IBM-SMI-Brazil/smi-brazil-assistant/blob/master/images/fsilveir.jpg" width="120">  | [Felipe Silveira](https://www.linkedin.com/in/fsilveira/) | fsilveir@br.ibm.com | IT Specialist
