# **Analysis of World's Unicorn Companies**

### Landscape of the World's Unicorn Companies as at April 2022. Microsoft Excel was used for the cleaning, exploration and visualization. Click [here](https://davidokenwa.medium.com/thoughts-behind-beautiful-dashboards-9fb8b24d9f6d) for full article.

## **Background and Dataset**
#### This dashboard was created in May 2022 as a submission for the Maven Unicorn Challenge. A unicorn company is a privately owned company with a valuation of more than $1B. The dataset was given by Maven Analytics (Click [here](https://maven-datasets.s3.amazonaws.com/Unicorn+Companies/Unicorn+Companies.zip) to download it ). It includes a CSV table with 1,074 records, one for each unicorn company in the world as at April 2022.

#### I was tasked to use a single-paged dashboard  to illustrate the current landscape of unicorn companies around the world.

### **Project Steps**

#### The steps I took to arrive at the final one-page dashboard are outlined below:
#### 1. Getting clarifications
#### 2. Cleaning the data
#### 3. Data exploration
#### 4. Making a sketch
#### 5. Data visualization
#### 6. Key insights

| ![project steps](https://github.com/davidokenwa/Landscape_of_World-s_Unicorns_2022/blob/main/project_steps.png) | 
| :--------: | 
| **Project Steps. Maven Unicorn Challenge.** _Designed by David Okenwa using PowerPoint_  |

### **1. Getting Clarifications**

Getting clarifications from relevant stakeholders is an important stage of the analysis. The stakeholders could be managers, co-workers, customers, HR personnel etc. You get clarifications by asking questions. Asking the right questions to the right people will help you clearly understand the problem you are solving and the stakeholders’ expectations. Before building the dashboard, I asked myself a series of questions about the data and answered them. However, while working for an organization, you should not answer the questions alone but get further clarifications from the relevant stakeholders. 

Some of the questions I asked are outlined below. 
1. What is the purpose of the dashboard?
2. Who is going to see the dashboard?
3. From the available data, what questions can I answer?
4. Which of the questions are most important?
5. What chart type should I use?

You can get my answers to these questions via the more detailed [article](https://davidokenwa.medium.com/thoughts-behind-beautiful-dashboards-9fb8b24d9f6d).


### **2. Data Cleaning**
I looked through the data to find possible missing data, wrong entries, incorrect data formats and duplicate data. 

To ensure a clean data, I formatted the "Valuation" and "Funding" columns as numbers, I replaced rows where funding was unavailable with the average funding, I split the "Select Investors" column into multiple columns each with a single investor and unpivoted it into a single row. I also added two new columns "Year joined" and "Years to unicorn" by applying simple functions and calculations to existing columns. 


### **3. Data exploration**

Here, I dug into the data to find patterns and infomation for myself. Not all the patterns observed during exploration were visualized.

### **4. Sketching**

Here, I sketched the dashboard's outline on an A4 sheet. I did this after exploration and after getting inspiration from other vizzes. It is a good practise to have a sketch before starting the dashboard.

| ![viz sketch](https://github.com/davidokenwa/Landscape_of_World-s_Unicorns_2022/blob/main/viz%20sketch_5.jpg) | 
| :--------: | 
| **Sketch of dashboard’s outline.** _By David Okenwa_  |


### **5. Data visualization**

I used pivot tables to get the graphs and charts, and formulas to get the single digits. Following visualization principles, I edited the default Excel charts to get a less cluttered and beautiful one. Some important visualization principles I followed include:

* Declutter the charts. Remove gridlines, unnecessary labels and unnecessary chart elements
* Direct readers’ attention to key points in each chart
* Replace generic titles with the main point of each chart
* Use a simple colour palette
* Tell a story

| ![dashboard](https://github.com/davidokenwa/Landscape_of_World-s_Unicorns_2022/blob/main/Unicorn_dashboard.png) | 
| :--------: | 
| **Maven Unicorn Dashboard.** _Designed by David Okenwa with Microsoft Excel_  |

### **6. Key insights**

Here are some of my insights from the dashboard:

* Fintech,  Software and AI are the best unicorns to invest in.
* It is possible to become a unicorn without external investment. It might take a while though.
* There is a recent surge in the number of unicorns.
* USA has more unicorns than the rest of the world combined.
* Could Africa be a fertile ground for unicorns if given more investment and attention?
---

### **Relevant Links**

* [Medium article](https://davidokenwa.medium.com/thoughts-behind-beautiful-dashboards-9fb8b24d9f6d)
* [LinkedIn Post](https://www.linkedin.com/posts/david-okenwa_david-okenwa-maven-unicorn-challenge-activity-6927624440948092928-wJd9?utm_source=linkedin_share&utm_medium=member_desktop_web)
* [Dataset](https://www.mavenanalytics.io/data-playground)
