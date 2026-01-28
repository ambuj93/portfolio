---
type: experience
organization: Skan AI
role: Business Intelligence Architect
start_date: 06-2024
end_date: present
employment_type: full-time 
location: Bangalore
primary_domains: [Process Mining, BI Strategy, BI Architecture, Data Warehousing]
primary_tools: [Datbricks, Power BI, Superset, Tableau, Postgres SQL, StarRocks, Cusrsor, python, pyspark]
seniority_level: lead | manager | architect
visibility_level: multi-team | leadership
---

## Context
- Skan AI is a process mining Fast Paced Starup which enables its customer to understand the processes and time utilization by the employees. It provides deep insights into actual processes across various applications, AI enabled data enrichment and powering AI agents.

- This role sits within the Data Platform Team, owning entire data and analytics platforms and decisions around the choice of technology, deployments and availability. Closely work with Product Leaders, COO and Customers for their data platform and analytics requirements.

- Work with large scale streaming and batch processed data generated from event clickstream on every keypress, click, scroll of the participants followed by AI assisted data enrichment pipelines. 

## Problems Owned
- Revamped critical Power BI dashboards for the largest client. The client had 3 years of clickstream stream data from Skan and merged with their own CRM and workforce data. Over a period of time this resulted in a very complex and slow dashboard/report. 
    - With no documentation or handover, I analyzed over 30 worksheets in Power BI dashboard with 70 tables and 350 measures nad 150 calculated columns. 
    - In 4 months I optimized the data model and dashboard by building strategic data ingestion pipeline in Databricks and Azure blob storage to fetch external data, jobs to santize and merge the data into a data warehouse to support the dashboard requirements.
    - Updated the Power BI Data Model to use Direct Query instaed of Import mode to boost the interactive performance and faster data availability.    

- Owned the Power BI platform as an expert, to ensure we can bring down the power bi capacity usage and its variable cost due to autoscaling during peak utilization. In addition, worked with Databricks Architect to associate entire data platform cost and narrow down the root-cause.
    - Identified long runnig and scattered refreshes through out the day, kept the power bi capacity and databricks sql warehouses busy almost 22 hours of the day. 
    - Built a data refresh startegy to align with dashboard usage and data pipelines to minimize the cost. Now dashboard refreshes happen only during a 5 hour window, ensuring adequate resouces are available.
    - Brought down the capacity usage from 85% to 45%, brought down Databricks DBU consumption by 58%.  

- Led the data anlytics platform strategy to transition to Apache Superset (Opensource BI Application). Defined the multi phase implementation roadmap, including tool evaluation, platform architecture, deployement strategy, data modeling strategy, visualisation starndards, governance, embeding in web production rollout plan.
    - Built the delivery capability in team by hiring a full-time Analyst, a Data Engineer and a Superset Consultant.
    - Closely worked with Product Managers for expected implementation, Engineering Managers for Embedding into the Web application and DevOps to ensure successful deployment and rollout of the new BI application.
    - This tool supported On-Prem deployment, for highly regulated clients. 

## Key Initiatives / Projects
- [PBI Doctor] - Vibe coded a python based GUI appliaction for winodws users. This app can extract meta data from Power BI project and build a technical document. It classifies tables into regular vs calculated, along with their M-Query and DAX. It identifies columns and measures wih thier DAX, their usage in DAX or relations or visuals. 
    -  With this app we started documenting all standard and customer dashboards. This enabled smoother handover and management of changes.
    - It led to simplification of data model by identifying unused columns and measrues. 
    - Presented this application and its use case in compay wide Townhall. Establishing myself as a thought leader, problem solver and builder.

- [Power BI Health Monitor] - Designed a dashboard to track the reports being published across the workspaces to ensure a governance layer. This dashboard covered 4 ojectives
    - Monitor Power BI Capacity usage across worksaces and reports. Highlights any degradation in perfromance to take proactive actions.
    - Monitor inactive and slow refreshing reports, for workspace cleanup and report optimization.
    - Monitor Report refresh time and Databricks job completion time to ensure the adherence to the BI strategy to refresh the reprots in sync with Databricks jobs and latest data availability.
    -  Monitor report failure rate with clear ownership to fix the issues proactively.

- [Designed Datawarehouse] - Designed and Architected the Datawarehouse to support large scale datasets in Databricks and Starrocks. Defined the schema, data granularity, SQL queries, materialized views and refresh frequencies. Moved the organization away from reporting based on transactional data.
    - This datawarehouse powers the AI insights and AI Analyst.
    - Captures late ariving data to enable incremental refresh on dashboards
    - Reduced the size of largest tables used for reporting by 98% size on disk and 70% less records.
    - Resulted in power bi reports to refresh 80% faster. 

- [Training and Mentoring] - Organized 3 grooming and knowledge sharing  sessions for working with Multi-million or Multi-billion records. Built the capability in a team of 10 Data Analysts who work with Clients to support their custom data requirements, ensuring the implementation of best practices.

## Impact & Outcomes
- Led the datawarehouse design and implemntation to move away from reporting on transactional data.
- Reduced report refresh time by 80%
- Reduced size of data required to build same dashboards by 98%
- Implemented incremental refresh by capturing late arriving data with timestamps. Optimising resource utilization. 
- Built and led a team of 3 analysts and 1 data engineers.
- Led another team of customer facing 10 analysts.
- Documented Data Warehouse queries, granularity, use case, meta data information for LLMs, 
- Documented checklist for best practices for power bi and superset reporting. 

## Tools & Technologies
- Databricks
- Power BI
- Superset
- POstgres SQL
- StarRocks
- Superset
- Notion
- Azure Boards
- Git/Repo
- Cursor
- LLM (chatgpt, claude, gemini, grok)

## Stakeholders
- COO and VP
- Client representatives
- Data Platform Architecht
- Engineering Managers

## Skills Demonstrated
- Analytics Platform Strategy
- Program Plannig and Execution
- Team Building and Capability Development
- Stakeholder Management 
- Executive Communication

## Learnings & Growth
- Data-warehouse architecture and modeling
- BI platform ownership and Optimization
- Large scale data handling and governance
- Tool Evaluation, implementation and cost effectiveness
