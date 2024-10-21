---
layout: post
title: Deciphering Big Data
subtitle: e-Portfolio and Reflective Summary
categories: 
tags:
---
This module covers techniques and tools for analyzing and interpreting large datasets, including methods for handling structured and unstructured data, data cleaning, visualization, and machine learning.

## Learning Outcomes:
1. Identify and manage challenges, security issues and risks, limitations and opportunities in data wrangling.
2. Critically analyse data wrangling problems and determine appropriate methodologies, tools and techniques (involving preparing, cleaning, exploring, creating, optimising and evaluating big data) to solve them.
3. Design, develop and evaluate solutions for processing datasets and solving complex problems in various environments using relevant programming paradigms.
4. Systematically develop and implement the skills required to be effective member of a development team in a virtual professional environment, adopting real-life perspectives on team roles and organisation.

## Artefacts
### Project 1: Collaborative Discussion Forum Summaries 

<strong>Description:</strong> The Data Collection Process. In this discussion, I critically evaluated the rationale behind the Internet Of Things (IOT), in the context of the article by Huxley et al (2020), highlighting the opportunities, limitations, risks and challenges associated with such a large-scale process of data collection. Please review Initial and Summary post on the Collaborative Discussion Forum.

<strong>Summary:</strong> Although I did not receive feedback from peers in this project discussion, reading insights from my peers' intial posts enabled me to improve my summary post. My peers had used real life case studies to improve their discussions so I did this as a form of feedback. I used a recent case study from Volvo Cars to further expand my summary. This project taught me to broaden my perspective on a large-scale process of data collection. An improvement that I would make is going into depth about this process in the chosen case study from Volvo Cars. Overall, the skills gained were: communication, literacy, critical reflection and research.

### Project 2: Data Management Pipeline Test

<strong>Description:</strong> This tested my knowledge of how data flows from source to analysis. I matched a Python concept/library with its purpose and I matched the Python practice with a description. I received a high grade.

<strong>Summary:</strong> I learned several key concepts and practical skills essential for preparing data for analysis. First, I gained a deep understanding of data quality, including the importance of accuracy, completeness, consistency, and reliability. This foundation helped me recognize the implications of poor data quality on analysis outcomes. I learned how to identify and handle missing values, exploring different types of missing data and various techniques for addressing them, such as imputation and deletion. Additionally, I became familiar with data types and structures, which allowed me to effectively identify the conversions and management of different data types. The skills gained were: time management and numeracy.

### Project 3: Development Team Project Report
<strong>Description:</strong> 
Creating a team dynamic online can be a challenge but this document gives you the tools you need to make the most of any team project or development activity.

### Project 4: Normalisation Task

<strong>Description:</strong> Normalising a table with un-normalised data to 3rd Normal Form (3NF).

<strong>Summary:</strong> To normalize the table to 3rd Normal Form (3NF), I began by ensuring the table was in First Normal Form (1NF) by verifying that each cell contained a single value and there were no duplicate rows. Next, for Second Normal Form (2NF), I removed partial dependencies by splitting the table into a "Students" table and a "Courses" table, separating the details related to students from the courses they were enrolled in. In Third Normal Form (3NF), I eliminated transitive dependencies by breaking down the "Courses" table further into two tables: one for student-course associations (Student Courses table) and another for course-specific information (Course Details table), like exam boards and teachers. By doing so, all non-key attributes now depend only on the primary key of their respective tables, completing the normalization to 3NF. Skills gained were: critical thinking and analysis, numeracy, problem solving.


| Student Number| Course Name   | Exam Score    |
|---------------|---------------|---------------|
| 1001          | Computer Science|  78  |
| 1001          | Maths  | 78 |
| 1001          | Physics  | 78  |
| 1002          | Maths  | 55  |
| 1002          | Biology | 55  |
| 1002          | Music  | 55 |
| 1003          | Computer Science  | 90  |
| 1003          | Maths  | 90 |
| 1003          | Physics  | 90 |
| 1004          | Maths  | 70  |
| 1004          | Physics  | 70 |
| 1004          | Biology  | 70  |
| 1005          | Computer Science  | 45 |
| 1005          | Maths | 45  |
| 1005          | Music  | 45  |

| Course Name      | Exam Board      | Teacher Name      |
|---------------|---------------|---------------|
| Computer Science | BCS | Mr Jones |
| Maths | EdExcel  | Ms Parker  |
| Physics  | OCR | Mr Peters  |
| Biology  | WJEC  | Ms Patel  |
| Music | AQA  | Ms Daniels |

### Project 5: Individual Project: Executive Summary
## Reflections

During our team project, tasks were distributed among the three of us based on our individual skills. My responsibilities included researching the organization’s background and database system requirements, organizing team meetings, and structuring the assignment in line with the learning outcomes. Initially, however, there was some overlap in task allocation. For example, the data management pipeline depended on the type of DBMS selected, and the latter stages of the pipeline were contingent on earlier steps. This created challenges in time management and communication, as some team members couldn’t begin their work until others had completed theirs.

Bruce Tuckman’s “stages of group development” (Tuckman, 2010) helped me understand the importance of effective teamwork and communication in an organisational context. We focused on open communication, using regular meetings and digital collaboration tools to facilitate idea sharing and timely feedback regarding our team goals, roles, and responsibilities. Building trust and collaboration was also key; we fostered an environment where everyone felt comfortable raising concerns and offering suggestions, which improved problem-solving and innovation. Additionally, we implemented regular feedback loops to assess our progress and make necessary adjustments, continuously improving our process. Applying these principles significantly enhanced our team’s effectiveness and the quality of our final database system.

While our group achieved a successful outcome, we could have improved further by sharing individual skills more openly. This would have encouraged more collaboration and input across tasks, leading to richer feedback and more cohesive work.

I was able to apply these lessons from the Unit 6 report to the Unit 11 executive summary. In Unit 11, I developed and applied professional skills to become a more effective team member within a group of software developers. Through extensive research, I learned the importance of GDPR and data integrity in business contexts. GDPR emphasises protecting and ensuring the privacy of personal data, while integrity ensures its reliability and accuracy. Both are critical in database design for legal compliance, security, and operational efficiency.

This knowledge broadened my perspective, helping me see database systems not only from a technical standpoint but also from a business perspective. Understanding that components of a database system evolve over time highlighted the importance of staying current with new policies and regulations. This is a valuable habit and skill that will serve me well as I pursue a career as a Data Scientist.

## Meeting Minutes
We initially followed the team contract procedure to establish skills between eachother in order to distribute tasks

## Professional skills matrix and action plan

Skills gained:
Problem-Solving: Developed the ability to identify common data wrangling challenges such as missing data, inconsistencies, and formatting errors.

Risk Management: Gained skills in recognizing and mitigating data security risks, especially concerning GDPR compliance and handling sensitive data.

Performance Evaluation: Gained experience in testing and optimizing solutions for speed, scalability, and accuracy.

Team Collaboration: Improved communication and collaboration skills by working effectively in a virtual team setting, using tools like UoE online portal, Whatsapp, and GitHub.

Data Transformation: Became skilled in techniques like imputation, normalization, and standardization to ensure data is prepared for analysis.

Action Plan:
I will continue to explore more advanced data wrangling techniques to enhance my ability to solve complex problems. I will actively seek out challenging datasets and case studies to apply these techniques in a practical setting.

I will focus on improving my knowledge of big data tools and frameworks to handle and optimize larger datasets. I will also work on developing more advanced techniques to enhance efficiency when dealing with high-volume data.

I will deepen my understanding of data privacy laws, especially GDPR, and continue to improve my ability to recognize security vulnerabilities in datasets. I will regularly review industry best practices for data encryption, anonymization, and secure data storage. Additionally, I will seek further training or certification in data security and compliance.

