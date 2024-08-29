# Glossary of Terms for Process Mining

## Sample Prompt

```
You are an expert at creating precise definitions of technical terms using.  
Your definitions are precise, concise, distinct and non-circular.  
You give a quick definition followed by an example.  
You always return the term name in a markdown level-4 
heading followed by the definition and example.

Please create a list of business terms for an application program that does process mining.  
Make sure the key terms are listed in alphabetical order.
```
## List of Terms

#### Activity

A specific task or action within a business process that contributes to the completion of that process. 

**Example**: In a purchase order process, activities might include "Submit Purchase Request," "Approve Request," and "Issue Payment."

#### Bottleneck

A point in a process where the flow of work is impeded, causing delays and reducing the overall efficiency of the process. 

In a hiring process, a bottleneck might occur during the interview scheduling phase if only a limited number of interviewers are available.

#### Case

An individual instance of a business process, often represented by a unique identifier, tracking all activities and events related to that instance.

 **Example**: Each purchase order processed by a company can be considered a separate case, tracked from initiation to completion.

#### Compliance

Adherence to laws, regulations, standards, or internal policies within a business process. 

**Example:** Ensuring that all financial transactions within a company are recorded and reported according to regulatory requirements is a matter of compliance.

#### Conformance Checking

The process of comparing the actual execution of a business process (as recorded in logs) against a predefined model to identify deviations or inefficiencies. 

**Example**: A conformance check might reveal that a step intended to be completed in three days took a week in actual practice, indicating a bottleneck.

#### Data Cleaning

The process of identifying and correcting errors, inconsistencies, or missing values in event data to ensure its accuracy and reliability for analysis. 

For example, data cleaning might involve removing duplicate entries or filling in missing timestamps in a log file.

#### Data Extraction

The process of retrieving specific data from various sources, such as log files, to be used for analysis or further processing. 

For instance, data extraction might involve pulling timestamped events from a server log to analyze system performance over time.

#### Data Integration

The process of combining event data from multiple sources or systems into a cohesive dataset for process analysis. 

For example, data integration might involve merging customer service logs with sales transaction logs to analyze the end-to-end customer experience.#### Data Transformation

The process of converting extracted raw event data into a structured format suitable for analysis, often involving normalization and aggregation. In a sales process, data transformation might involve standardizing date formats and combining multiple event logs into a unified dataset.

#### Event

A record of a specific occurrence or action within a process, often timestamped and associated with a particular case. 

For example, the event "Order Shipped" marks the time when an order is dispatched from the warehouse in an order fulfillment process.

#### Event Correlation

The process of linking related events across multiple log files or sources to provide a complete view of a process instance. 

In an IT monitoring process, event correlation might link an "Error Logged" event with a subsequent "System Restarted" event across different systems.

#### Event Data

The raw information that records individual occurrences within a business process, typically stored in log files and used as the basis for process mining. 

In a customer service process, event data might include entries like "Call Received," "Ticket Created," and "Issue Resolved."

#### Event Filtering

The process of selecting specific events or types of events from a log file to focus on relevant data for analysis. 

For instance, event filtering might be used to isolate only the "Payment Received" events from a broader set of e-commerce transaction logs.

#### Event Log

A chronological record of all events or activities associated with a business process, typically used as the primary data source in process mining. 

**Example**: An event log for an online order process might include timestamps for when the order was placed, confirmed, shipped, and delivered.

#### Event Log Management

The process of collecting, storing, and organizing log files to ensure that event data is readily accessible for analysis. 

For example, event log management might involve setting up automated processes to archive older logs while maintaining access to recent logs for process mining.

#### Key Performance Indicator (KPI)

A measurable value that indicates how effectively a process or organization is achieving its objectives. 

For example, the average time to resolve customer support tickets is a KPI that reflects the efficiency of the support process.

#### Lead Time

The total time taken from the initiation of a process to its completion, including both active working time and any delays. 

In a manufacturing process, lead time includes the time from receiving an order to delivering the finished product to the customer.

#### Log Parsing

The process of analyzing and interpreting log files to extract structured event data for further analysis. 

For example, log parsing might involve identifying and isolating key events such as "Login Success" or "File Upload" from a web server log.

#### Process Discovery

The technique of automatically generating a business process model from event log data, revealing the **actual** workflow as executed.

Very often the documented workflows do not follow the actual worklows.

**Example**: By analyzing the event logs, process discovery might show that orders are often rerouted through additional approval steps not initially considered in the formal process.

#### Process Instance

A single execution of a business process, from start to finish, capturing all related activities and events. 

Each customer's journey through a loan application process represents a separate process instance.

#### Process Mining

A data-driven technique used to analyze and improve business processes by extracting insights from event logs. 

A company might use process mining to identify inefficiencies in their procurement process by analyzing the time taken at each step.

#### Process Model

A formalized representation of a business process, often visual, showing the sequence of activities, decision points, and flow of information or materials. 

**Example**: A process model for handling customer complaints may include steps like "Receive Complaint," "Assess Issue," "Assign to Representative," and "Resolve Complaint."

#### Process Optimization

The practice of making changes to a process to improve its efficiency, effectiveness, or adaptability. 

For instance, automating certain repetitive tasks in a payroll process can be a form of process optimization that reduces processing time.

#### Resource

Any entity (person, machine, system) that performs or supports activities within a business process. 

**Example**: In a manufacturing process, resources might include operators, assembly line robots, and quality control software.

#### Root Cause Analysis

A method used to identify the fundamental reason for a problem or defect within a process. If customer complaints about late deliveries are increasing, root cause analysis might reveal that delays in the supply chain are the primary issue.

#### Throughput Time

The total time taken from the start to the end of a process or case, encompassing all included activities and delays. 

**Example**: If a customer service ticket is opened on Monday and resolved on Wednesday, the throughput time for that ticket is two days.

#### Timestamp

A specific date and time recorded for each event within a log file, used to sequence and analyze the flow of activities within a process. In a shipping process, a timestamp might record the exact moment a package was dispatched from the warehouse.

#### Variant

A unique sequence of activities that occurs in a business process, representing a specific way in which the process is executed. For instance, in an insurance claim process, one variant might involve direct approval, while another requires further investigation before approval.

