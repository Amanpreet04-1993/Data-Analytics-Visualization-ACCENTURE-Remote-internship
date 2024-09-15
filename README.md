# Data-Analytics-and-Visualization - ACCENTURE-Remote Internship
![Acc_Logo](https://github.com/user-attachments/assets/a6a12bec-098e-456e-bda6-338da5dab11c)


*Task 1: Project Understanding*

What you'll learn-

What are the responsibilities of a Data Analyst at Accenture.
What is a typical project team structure.
How to review a client project brief.

What you'll do-

Meet your Accenture team, including the industry, IPO and data experts
Read and analyze a client project brief to understand the client and business problem, identify the requirements that need to be delivered, and identify which tasks you need to focus on as a data analyst

let's get started!

Here are some key facts about this program:

    You are working as a Data Analyst at Accenture.
    You work within a larger team, where each member has a different role and level of responsibility.
    Your team has been assigned a new project for a client called (Social Buzz).
    this is an exciting opportunity for you to showcase your data analysis and visualization skills.


Your first task is to read the brief from Social Buzz and complete a short knowledge check before the call. 

One of Accenture’s Managing Directors, Mae Mulligan, is the client lead for Social Buzz.

She has reviewed the brief provided by Social Buzz and has assembled a diverse team of Accenture experts to deliver the project.

Mae has scheduled a project kick off call with the internal Accenture project.

Ahead of the call, Mae has shared the project brief so you can get up to speed on what Social Buzz need help with.

Read the brief to:

    Understand the client and business problem at hand.
    Identify the requirements that need to be delivered for this project.
    Identify which tasks you should focus on as a Data Analyst.


Complete the knowledge check to move onto the next step. 

You can attempt each question in the knowledge check as many times as you like!

[Data_Analytics Client Brief.pdf](https://github.com/user-attachments/files/17006066/Data_Analytics.Client.Brief.pdf)

    Question 1
    Which statement best describes the business problem that Accenture is tasked to address for this project?
    Ans - The client has reached a massive scale within recent years &
    does not have the resources internally to handle it.
  Spot on, the client stated that scale was a big problem of theirs &
    they are struggling to manage the scale with the resources that they currently have. 
    The brief said that the client is looking for help with the management of their journey into such a large scale.
      
    Question 2
    Which statement lists the three requirements that Accenture is tasked to fulfill for this project?
    Ans - Audit of big data practice, recommendations for IPO, analysis of popular content

![SS](https://github.com/user-attachments/assets/1086faab-8666-48ae-a11d-6cc483b44eae)

: Project Understanding

    Question 1
    Which task out of these options is the most relevant to you as a data analyst, and therefore which one will you work on?
    Ans - Analysis of sample data sets with visualizations to understand the popularity of different content categories
This is exactly the task a data analyst would be focusing on and this is what you will be working on!


**********************************************************************************************************************************

*Task 2: Data Cleaning & Modeling*

What you'll learn

How to clean, model and analyze data to create valuable insights for the client 

What you'll do

Identify which datasets will be required to answer the client’s business question
Clean the datasets and merge them to prepare the data for analysis
Determine the answer to the client’s business question

Let's dive into the data, The client has sent through:

    7 data sets - each data set contains different columns and values
    A data model - this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.
   
There is a lot of information here and it’s easy to get lost in the data. 
So, to make sure you are using the right data to answer the business questions 
you’ll follow these steps:

    1. Requirements gathering
    2. Data cleaning
    3. Data modelling

First up, requirements gathering

As we mentioned, you have been sent 7 datasets and a data model.

Often you won’t need all these datasets to find what you’re looking for.

So, the first step is to use this data model to identify which datasets will be required to answer your business question - 
which is to to figure out the top 5 categories with the largest popularity.

[Data model - Task 2.pdf](https://github.com/user-attachments/files/17006311/Data.model.-.Task.2.pdf)

Definitions of different data types:

    String - Sequence of characters, digits, or symbols—always treated as text
    UUID - Universally Unique Identifiers
    Array - List with a number of elements in a specific order—typically of the same type
    Integer - Numeric data type for numbers without fractions
    Timestamp - Number of seconds that have elapsed since midnight (00:00:00 UTC), 1st January 1970 (Unix time)

Source: Direct extract from Amplitude -   https://amplitude.com/blog/data-types

    Question 1
    Which three data sets will you need to complete your analysis?
    Ans - Reaction, Content, Reaction Types


Data sets - Quick Explanation

You’ve identified Reaction, Content, and Reaction Types as our relevant data sets.

To clarify why you made this selection:

    1. The brief carefully it states that the client wanted to see 
      “An analysis of their content categories showing the top 5 categories with the largest popularity”.
     2. As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
      3. We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
       4. So, to figure out popularity, we’ll have to add up which content categories have the largest score.

But! Before we begin to work with the data sets, we’ll need to ensure that the data is clean and ready for analysis…

Data Cleaning-

Data cleaning is a common and very important task when working with data.

What you need to do:

First: Open the three data sets below - (Raw File)

[Uploading ReactionTypes (1).csv…]()

[Uploading Reactions (1).csv…]()

[Uploading Content (1).csv…]()

**Data Modelling 
**
Now we want to figure out the top 5 categories. To complete your data modelling, follow these steps:

1. Create a final data set by merging your three tables together

       Ans -  “VLookUp” formula - the Reaction table as base table,
        first join the relevant columns from your Content data set, and then the Reaction Types data set.
 
3. Figure out the Top 5 performing categories

       Ans -  Added up the total scores for each category  “Sum If” formula

4. The end result should be one spreadsheet which contains:

A cleaned dataset
The top 5 categories
 
Tool :  Excel (To create your final data set)
**************************************************************************************************************************************************************************
  **Final Master File** -   [Task 2 master copy (Data Modelling).csv](https://github.com/user-attachments/files/17007094/Task.2.master.copy.Data.Modelling.csv)
**************************************************************************************************************************************************************************


