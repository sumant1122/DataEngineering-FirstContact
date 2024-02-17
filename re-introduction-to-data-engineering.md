# Re-Introduction to Data Engineering

Why re-introduction?

Data engineering introduction is scattered all over the internet. It tells you the overview of the field.

The re-introduction aims to apply those ideas to your project and start seeing your project in a new light.

### **Data Engineering involves the design and construction of systems for collecting, storing, and analyzing data.**

Great, that’s what DE is for right? But what is your project doing in this case?

Lets breakdown.

**Design**: What architecture is your project using?

**System**: Which specific infrastructure/hardware is your project using?

**Collecting**: What is being collected, how is it being collected, and from where is it being collected?

**Storing**: Where is the data being stored, are there any intermediate storages, how is the Data Warehouse set up?

**Analyze**: What business case are you trying to solve? What downstream processes are consuming the data? Which teams are involved in the whole process?

### Data Engineers work on the architecture of data systems, extract data from various sources, and ensure that it is in a suitable format for analysis.

**Architecture**:

Before running the DE system, it needs to be created or architected in a way to provides meaningful information to all the systems that connect to it.

Some examples of Architecture are :

* **Lambda Architecture:** This architecture includes batch and speed layers, allowing for both real-time and historical data analysis.
* **Kappa Architecture:** In this architecture, all data is treated as a stream, simplifying the architecture and making it more suitable for real-time processing.
* **Data Lake Architecture:** This architecture stores all types of data (structured and unstructured) at any scale. It allows for different types of analytics, from dashboards and visualizations to big data processing, real-time analytics, and machine learning.

**Data Systems:**

Data systems are crucial components that handle the storage, retrieval, and processing of data. They are designed to efficiently manage large volumes of data and support complex queries and transactions. The design of a data system often depends on the specific requirements of the data engineering project, including the volume, velocity, and variety of the data, as well as the types of analyses that need to be performed.

**Storage:**

Data storage involves the design, construction, and use of data storage systems to support data processing and analysis. Data engineers use various data storage technologies, such as relational databases, NoSQL databases, and data warehouses, to store and manage large volumes of structured and unstructured data. They ensure data is stored efficiently, securely, and with appropriate access controls. Data storage systems must also be scalable and fault-tolerant to handle the increasing volume and complexity of data.

**Retrieval:**

Data retrieval involves efficiently and accurately extracting data from various sources to support data analysis and decision-making. Data retrieval techniques include data querying, data mining, and data warehousing. Data engineers design and implement data retrieval systems that can handle large volumes of data from diverse sources, ensuring data accuracy, completeness, and timeliness. They also ensure that data retrieval systems are scalable, fault-tolerant, and secure, with appropriate access controls.

**Processing:**

Data processing involves the transformation and manipulation of raw data into a usable format for analysis and decision-making. Data processing techniques include data cleaning, data transformation, and data integration. Data engineers design and implement data processing systems that can handle large volumes of data from diverse sources, ensuring data accuracy, completeness, and consistency. They also ensure that data processing systems are scalable, fault-tolerant, and secure, with appropriate access controls.

### Data Engineers also create and maintain data pipelines, which involve cleaning, structuring, and enriching raw data.

**Creating Pipelines:**

Creating data pipelines involves the process of automating the flow of data from one place to another. Typically, it starts by extracting data from various sources, then transforming it into a more usable state, and finally loading it into a database or data warehousing service. This process, often abbreviated as ETL (Extract, Transform, Load), is fundamental in data engineering. It allows for the efficient and regular transfer of data, which is crucial for maintaining up-to-date analytics and insights.

**Maintain pipelines:**

Maintaining data pipelines is an essential part of a data engineer's role. This involves monitoring the pipelines to ensure data flows correctly and fixing any issues that may arise. Regular maintenance can help identify potential problems before they escalate and affect the system's functionality. It also involves updating the pipelines as needed, to accommodate changes in data sources or shifts in organizational needs and objectives.

**Raw Data:**

Raw data refers to unprocessed or unclean data directly collected from various sources. It hasn't been analyzed or processed, meaning it often contains errors, outliers, or irrelevant information. In the context of data engineering, raw data is transformed and cleaned in the data pipeline to be suitable for analysis.

**Cleaning Data:**

Cleaning data refers to the process of preparing and cleaning raw data for analysis. This involves identifying and correcting errors, removing duplicates and outliers, dealing with missing data, and ensuring consistency in the dataset. The aim is to improve the accuracy and reliability of the data, making it suitable for further analysis and interpretation.

**Structuring Data:**

Structuring data refers to the process of organizing raw data into a format that is more suitable for analysis. This could involve formatting data into rows and columns, categorizing data into relevant groups, or hierarchically arranging data. The structured data is often stored in relational databases, making it easier to query and extract useful information. Structuring data is a crucial step in the data pipeline as it ensures the data is in a usable state for further analysis.

**Enriching Data:**

Enriching data refers to the process of enhancing raw data with additional information or context, making it more valuable for analysis. This could involve adding new variables, integrating data from other sources, or using algorithms to derive new insights from the existing data. The aim is to increase the depth of understanding that can be obtained from the data, leading to more accurate and meaningful insights.

### Re-re-introduction to Data

Again, what is this data about?

The questions to ask from the perspective of the project are what data is being ingested?

Data may include all the related information which is of importance to business.

That being said, the logs from your services/microservices are also data, but the business has no use for that. But, if a service/microservice is processing events then those are essential. You need a way to store those events and then apply the DE to persist for further analysis.

**Data Ingestion:**

Data ingestion refers to the process of collecting and importing data for immediate use or storage in a database. The data can be ingested in real-time (streaming) or in batches. Real-time ingestion involves importing data as soon as it is produced, providing up-to-date information. On the other hand, batch ingestion involves importing data at regular intervals, which can be less resource-intensive. The choice between these methods depends on the specific needs of the project.

**Data Format:**

In data engineering, both structured and unstructured data are used. Structured data is organized in a predefined manner, often in rows and columns, and is generally stored in relational databases. Unstructured data, on the other hand, does not follow a specific format and can include text, images, videos, and more.

**Structured Data Examples :**

* CSV Files
* XML Files
* JSON Files

**Unstructured Data Examples :**

* Text Files
* Email
* Webpages
* Images
* Videos
* Audio files

### Why All This

Data Engineering is crucial for making data-driven decisions, as it ensures data is reliable and available for analysis.

**Data-Driven Decisions:**

Decisions that are based on data analysis and evidence rather than intuition or guesswork. These decisions are made by collecting, analyzing, and interpreting data to identify patterns, trends, and insights that can inform decision-making. Data-driven decisions are typically more accurate, consistent, and objective than decisions made without data. They can help organizations to identify opportunities, make informed decisions, and optimize their operations.

To make data-driven decisions, organizations need to have effective data management and analysis capabilities, including data storage, retrieval, and processing systems, as well as data analytics tools and techniques.

**Data Analysis:**

Data analysis involves techniques to analyze data, including machine learning, statistical modeling, data mining, and data visualization.

***

_This was a no-tech jargon-based introduction to data engineering._
