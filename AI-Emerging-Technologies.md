---
layout: post
author: Gavin Van Horn
tags: [cscc] 
---

### [AI and Emerging Technologies]
a. The emerging technology I chose to highlight is automated data ingestion tools. As a data engineer, I've seen a shift in the way our data team operates on a day-to-day basis. In our database platform, Snowflake, we are exploring opportunities to fully automate our ingestion process using Cortex Code (Snowflakes native AI) and OpenFlow. Though this attached video is 1 year old, it does show the capabilities of OpenFlow prior to the addition of Cortex Code to the Snowflake infrastructure, [OpenFlow](https://www.youtube.com/watch?v=EifXoWUsreA). Now with Cortex Code added, the engineer can simply give natural language commands, and it will build, and monitor, the data ingestion process. Though we haven't fully implemented this solution in our environment, we are heavily relying on Cortex Code to speed up our DDL generation and speed to ingestion.
b. Prior to the AI implementation in Snowflake, our development process was very manual. We currently still use Streamsets, which is incredibly manual for data ingestion. It is a drag-and-drop pipeline builder, which currently has no AI capabilities. In terms of the DDL generation for our ingestion process, prior to Cortex Code, we were writing the code by hand, which can be very time consuming. We also have a metadata driven platform, including using metadata to generate views, which required one entry per column on the table. I would say prior to the implementation of Cortex Code, our development process for one table in an existing source could take anywhere from 8 to 16 hours. Now, I would say that time is cut in half at the least.
