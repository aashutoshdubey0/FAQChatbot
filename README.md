# Columba Code FAQ (by AD)

Columba Code FAQ is an end-to-end Language Model (LLM) project leveraging Google Palm and Langchain technologies. The primary goal is to develop a robust Question and Answer (Q&A) system tailored for the e-learning domain, specifically designed for an organization akin to Codebasics (website: codebasics.io). Codebasics specializes in offering data-related courses and bootcamps, with a substantial learner base currently engaging through Discord or email for queries. This project aims to streamline the interaction process by providing a Streamlit-based user interface where students can pose questions and receive rapid responses.

## Project Highlights

- Integration of real FAQs from Codebasics, stored in a CSV file, to ensure relevance and authenticity.
- Utilization of Langchain and Google Palm to create an advanced Q&A system.
- Reduction of workload for human staff by implementing an LLM-based system.
- Seamless experience for students, allowing them to ask questions directly and receive instant responses.

## Some Screen Shots

![1](https://github.com/aashutoshdubey0/FAQChatbot/assets/99739350/87c4863a-0bf2-4e61-93d7-edd5019ec038)

![2](https://github.com/aashutoshdubey0/FAQChatbot/assets/99739350/810ea101-f384-4f23-90b3-fd2a9f98d2f2)


![3](https://github.com/aashutoshdubey0/FAQChatbot/assets/99739350/da6af2ec-86fe-4054-9986-2689da0d2fc7)

## Sample Questions

- Do you provide internships, and do you offer EMI payments?
- Do you have a JavaScript course?
- Should I learn Power BI or Tableau?
- Can I use Power BI on my MAC computer?
- I don't see Power Pivot; how can I enable it?

## Project Structure

- main.py: The main Streamlit application script.
- langchain_helper.py: Contains all the Langchain code.
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your Google API key.
