# Azure Text Translator with Python
This project is a Python-based solution that performs text extraction and processing from Word documents and web pages, followed by automatic translation using Azure Cognitive Services Translator. The solution integrates API consumption, content processing, and file automation, applying practical back-end concepts, cloud service integration, and textual data manipulation. The code was developed in a modular way, aiming for future evolution into a web-based application.

## Motivation
This project was developed as part of a Project Challenge (Lab) on the DIO platform. The challenge aims to teach how to build an automatic translation solution for technical articles using Azure AI, with a focus on terminological accuracy and preservation of domain-specific context, facilitating access to specialized content in different languages.

## Project Setup and Execution
The project deliverable consists of a single Python file containing the complete implementation of the solution. Before submission to GitHub, all sensitive information related to Azure accounts, including subscription keys, endpoints, regions, as well as the specific files and URLs used for translation, was removed or replaced. After downloading the project, users must configure these values according to their own Azure account and translation requirements.

The code was developed and tested using Google Colab. For users who do not intend to adapt the project to a different environment, running the script directly in Google Colab is recommended, as it ensures compatibility and simplifies execution.

## Project Objectives
- Develop a practical automatic translation solution using cloud-based AI services  
- Apply concepts of API consumption and integration with Azure Cognitive Services  
- Perform text extraction, cleaning, and normalization  
- Automate the translation of technical content from different sources  
- Structure the code in a modular and extensible way  

## Features
- Text extraction from Word documents (.docx)  
- Text extraction and cleaning from web pages  
- Removal of irrelevant elements such as scripts and styles  
- Automatic translation from English to Portuguese using Azure Translator  
- Generation of translated Word documents  

## Technologies Used
- Python  
- Azure Cognitive Services Translator  
- Requests  
- BeautifulSoup  
- python-docx  
- Google Colab  

## General Workflow
1. Text is extracted from a document or URL  
2. The content is cleaned and normalized  
3. The processed text is sent to the Azure Translator API  
4. The translated content is returned or saved as a new file  

## Future Improvements
- Development of a web-based interface for user interaction  
- Support for multiple source and target languages  
- Automatic language detection  
