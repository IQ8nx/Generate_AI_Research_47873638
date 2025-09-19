# Generative_AI_Research_47873638   

##  Repository Overview  
This GitHub repository acts as a centralized storage and collaboration hub for all materials related to the research study **"Using Generative AI Tools - Boon or Bane"**. It organizes diverse research assets (data, code, documents, media) into a logical structure to support seamless team collaboration, maintain version control, and enable quick access to resources—ensuring the research process is efficient, transparent, and easy to replicate.  


##  Folder Structure & Content Guide  
| Folder Name               | Core Purpose                                                                 | Example Files                                                                 |
|---------------------------|-----------------------------------------------------------------------------|-------------------------------------------------------------------------------|
| `Literature_Review`       | Stores academic and reference materials for background research, including peer-reviewed journal articles, conference papers, book excerpts, and industry news relevant to generative AI. | `IEEE_Generative_AI_Ethics_2024.pdf`, `Book_Chapter_AI_Tools_Impact.txt`, `Literature_Review_Summary.md` |
| `Quantitative_Analysis`   | Contains all assets for quantitative research: survey questionnaires, raw/cleaned survey datasets, analysis scripts (Python/R), and the final quantitative report. | `Generative_AI_Survey_Questions.docx`, `Survey_Data_Cleaned_May2024.csv`, `Survey_Analysis_Script.py`, `Quantitative_Results_Report.pdf` |
| `Qualitative_Analysis`    | Houses materials for qualitative research: anonymized interview transcripts, interview protocols, participant consent forms, thematic analysis reports, and data visualizations (e.g., theme charts). | `Interview_Transcript_Participant05.txt`, `Interview_Protocol_Guide.docx`, `Participant_Consent_Form_Template.pdf`, `Thematic_Analysis_Chart.png` |
| `Drafts_Reports`          | Tracks draft and final research outputs: research proposals, conference paper submissions, and the comprehensive final study report (with revisions). | `Research_Proposal_Draft_v2.md`, `Conference_Paper_IEEE_Submission.pdf`, `Final_Study_Report_June2024.pdf` |
| `Additional_Materials`    | Stores supplementary resources that support the research (non-core but critical): participant information sheets, research process photos, team meeting minutes, and project timelines. | `Participant_Info_Sheet.pdf`, `Research_Workshop_Photo.jpg`, `Team_Meeting_Minutes_April2024.md`, `Project_Timeline_Gantt.csv` |


##  Collaboration Guidelines  
###  File Naming Convention  
To ensure consistency, readability, and compliance with best practices (referenced from Harvard Data Management Guidelines), all files must follow this format:  
`[File_Type]_[Content_Description]_[Date/Version]_[Optional_Details].FileExtension`  

- **Examples**:  
  1. `Survey_Data_Raw_April2024.csv`  
  2. `Interview_Transcript_Participant03_Version1.txt`  
  3. `Draft_Research_Proposal_v3_Revised.pdf`  

- **Avoid**: Vague names like `data.csv`, `report.pdf`, or `notes.txt`—these slow down collaboration and cause confusion.  


###  Git Workflow Rules  
1. **Pull First, Edit Later**: Always pull the latest changes from the remote repository before modifying files to avoid merge conflicts. Use the terminal command:  
   ```bash
   git pull origin main
