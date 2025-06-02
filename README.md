# RPA-LoanApplicationProcess

**Client:** UiBank  
**Tools:** UiPath Studio (REFramework with Excel), UiPath Orchestrator, Microsoft Excel, Gmail, Microsoft Edge, Windows 10 VM.  
**Project Type**: Unattended Robot | Deployment: Scheduled via Orchestrator  

**Project Overview:**   
Developed and deployed an unattended RPA solution to automate the end-to-end loan application processing workflow for UiBank, handling high-volume personal loan requests. The automation was designed to minimize manual intervention, reduce processing time, and improve compliance with business validation rules.  

**Responsibilities:**  
●	Analyzed and understood the As-Is and To-Be process flows defined in PDD & SDD.  
●	Automated data extraction from Outlook emails and reading of attached CSV files containing loan application data.  
●	Automated data entry into the UiBank Loan Web Application using UI automation.  
●	Implemented validation rules (e.g., age checks, income multiplier checks, loan term restrictions).  
●	Generated Loan IDs for each valid application and sent a consolidated response via email.  
●	Designed robust exception handling for business exceptions (e.g., missing attachments, invalid age/income).  
●	Utilized Orchestrator for scheduling, credential handling, and logging.  

**Achievements:**  
●	Reduced loan processing time by over 80%.  
●	Delivered a fully unattended bot with centralized logging (Kibana, Orchestrator).  
●	Created a modular, reusable workflow architecture adhering to best practices in scalability and error recovery.  
●	Ensured seamless exception reporting and retry mechanisms for known/unknown errors.  

