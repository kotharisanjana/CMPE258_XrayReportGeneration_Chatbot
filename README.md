# CMPE258 Term Project 
## Chest x-ray Report Generation and Chatbot

#### Team:
Ctrl Alt Del

#### Members:
* Ananya Joshi
* Sanjana Kothari
* Neetha Sherra
* Naga Bathula

#### Project Goals:
The objective of this project is to leverage the power of large language models for generating textual medical reports from chest x-ray images. By utilizing the multimodal capabilities of large language models, we aim to develop an application that takes a chest x-ray image as input and generates a medical report from the x-ray, in a similar fashion as a physician or medical practitioner would. In addition to that, we also provide a chatbot facility built using Microsoft’s Semantic Kernel that can look at the generated report and answer user questions based on the report as well as answer other general queries about chest-related questions. Therefore, it is a complete package that gives the user the diagnosis and observations from chest x-ray as well as give the user the ability to get specific answers to their questions about the report or general chest-related conditions.

#### Images
Location: ../Images/

https://openi.nlm.nih.gov/imgs/collections/NLMCXR_png.tgz

#### Reports
Location: ../Reports/

https://openi.nlm.nih.gov/imgs/collections/NLMCXR_reports.tgz

#### App snapshots:
![Screenshot from 2023-05-17 15-39-41](https://github.com/kotharisanjana/CMPE258_XrayReportGeneration_Chatbot/assets/60322201/e0f391b7-dcb2-4a3e-b577-c900304101fe)

![Screenshot from 2023-05-17 15-39-53](https://github.com/kotharisanjana/CMPE258_XrayReportGeneration_Chatbot/assets/60322201/e7b6b2fb-b790-4eb6-9632-68b5763b3a92)

![Screenshot from 2023-05-17 15-40-15](https://github.com/kotharisanjana/CMPE258_XrayReportGeneration_Chatbot/assets/60322201/007a4a01-89ed-4919-a04f-bcfe29ea2246)

#### To run the applicaton
1. Clone repo.
2. Add chest x-ray images in Images folder and reports in Reports folder at root level.
3. Add OpenAI api key to config.py in Code folder.
4. Install requiremnts.txt
5. To run, navigating into the Code folder and use 'streamlit run frontend.py

#### Models
https://drive.google.com/drive/folders/1kqEZm906iXJefqE7o03wycBx2D2jw12w?usp=share_link
