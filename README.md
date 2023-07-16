# MLOps-NLP-Assignment
An MLOps NLP Case Study to create an end-to-end MLOps pipeline for building a custom CRF Model to predict the treatment for a disease.


## Table of Contents
* [General Info](#general-information)
* [Project Contents](#project-contents)
* [Conclusion](#conclusion)
* [Software and Library Versions](#software-and-library-versions)
* [Acknowledgements](#acknowledgements)


### General Information
You are working as a data scientist for a Health Tech company called BeHealthy. It is a late-stage startup.

BeHealthy provides a web-based platform for doctors to list their services and manage patient interactions. It provides various services for patients, such as booking interactions with doctors and ordering medicines online (Similar to 1mg, PharmEasy).

Here, doctors can easily manage appointments, track past medical records and reports and give e-prescriptions.

We can assume that BeHealthy has enrolled thousands of doctors across the major cities in India. You can also assume that millions of patients are using BeHealthy’s services; hence, a lot of free-text clinical notes would be present in the e-prescriptions.

BeHealthy would want to convert these free-text clinical notes to structured information for analytics purposes. You have seen such a problem in your previous courses on NLP. You had created a CRF model to recognise the Named Entity in the medical data set.
 
**Clinical Note**: “The patient was a 62-year-old man with squamous cell lung cancer, which was first successfully treated by a combination of radiation therapy and chemotherapy.”

* **Disease**:  Lung Cancer<br>
* **Treatment**: Radiation Therapy and Chemotherapy

Before solving any business problem, we must always keep in mind that why a business needs to resolve the problem. In many cases, data scientists directly jump to the solution, using data sets like Kaggle competitions. But in the real world, you should be able to justify the business need, define KPIs and then design an optimal solution.


#### Data Set Brief Information
The data set contains snippet of medical data that may be generated when a doctor is writing clinical notes to his/her patient or as a review of a therapy that he or she has done.


#### Business Objective
Currently, if you need to extract diseases and treatments from free text, a trained person with clinical knowledge must manually look at the clinical notes and then pull this information.

A data entry team would manually look at the clinical text and extract information about diseases and their treatment data. A data validation team would validate the extracted information. This process is prone to errors, and as the data increases, the data-entry team’s size would need to be scaled up.

Automating this process would result in reduced man-hours. The data-entry team would not be required. The data validation team would still need to perform validation on extracted data. It would also significantly reduce manual errors.


#### Business Solution
Create an end-to-end MLOps pipeline for building a custom CRF Model to predict the treatment for a disease.


### Project Contents
* **BeHealthy Case Study.pdf** - PDF File explaining all answers to the questions given for case study.
* **README.md** - Readme file


### Conclusion
Answered all questions in detail and explained MLOps end-to-end pipeline structure.


### Software and Library Versions
No software or libraries was used for this case study.


### Acknowledgements
This case study is an assignment, done as part of [Upgrad](https://www.upgrad.com/ ) - **Master of Science in Machine Learning & Artificial Intelligence** programme.


### Contact
Created by [Sanjeev Surendran](https://github.com/Sanjeev-Surendran)


<!-- ## License -->
<!-- This project is not a open source and sharing the project files is prohibited. -->
