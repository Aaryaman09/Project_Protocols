# Project Protocols:
Steps you need to take to creating a project. 
  
## Steps:
* DATA SHARING AGREEMENT : (For data validation)
  1. Number of files.
  2. Mode of data transfer.
  3. Feature Details.
  4. Language.
  5. Nomenclature of file, extension of file, dtpe of each feature, number of feature, name of column.
  6. Null check.

* HIGH LEVEL DESIGN : 
  1. Low level gathering of idea i.e. end-product.
  2. Business Understanding/ Clients requirements.
  3. Dataset requirements/ Is dataset available ? Batch, Mini Batch, streaming, source, DSA.
  4. Number of files.
  5. Describe of data/ Dataset description.
  6. Block Diagram of system/infrastructure.
  7. Tech i will be using.

* LOW LEVEL DESIGN :
  1. Custom Architecture.
  ![alt text](https://user-images.githubusercontent.com/31642776/219688026-98ad2186-75a4-4897-8d7d-e4ba7e14506c.png)
  2. Explaing everything in HLD in details. Ex. What is the schema, what is the column name, column dtype, what checks will be performed, preprocessing, db operation,    what optimization will be performed. 

* ARCHITECTURE
  1. Thing to think about : Data ingestion, business requirements, their infrastructure, load of data, latency, frequency of data, scalability, security.
  2. Tools to select : Data Base, Cloud Platform, API, Monitoring tool, Security tool.
  3. Multiple level architecture: preprocessing complele steps (which db triggered, input and output, final design, processing engine), etc

* WIREFRAME
  1. How end product looks like.

* KPI : Key Performance indicator
  1. What are the expectation of business/business end goal. Put them as key indicator so client can see them in easiest possible way through dashboard etc.

* PIPELINE
  1. Design the overall theoratical pipeline with loose ends covered.

* CODING
  1. Split the whole pipeline in small blocks and complete each block.

* AUDIT
  1. Combine all blocks of code and check all protocols were followed or not.
* PRODUCTION
  1. Push the code in production.
  
* HYPERCARE
  1. Monitor, fix bug and add new feature.
