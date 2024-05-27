# Megaline Marketing Sales Analyze
## by _Mila Widya Lestari_

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

## Features
> #### Table users (user data):
> * user_id — user ID
> * first_name — user's first name
> * last_name — user's last name
> * age — user's age (in years)
> * reg_date — subscription start date (dd, mm, yy)
> * churn_date — date when user stopped using the service (if the value is missing or empty, the service was still being used when the data was collected)
> * city — user's city of residence
> * plan — name of the plan
>   
> #### Table calls (call data):
> * id — unique call ID
> * call_date — call date
> * duration — call duration (in minutes)
> * user_id — user ID who made the call
> 
> #### Table messages (SMS data):
> * id — unique SMS ID
> * message_date — message date
> * user_id — user ID who sent the SMS
>   
> #### Table internet (web session data):
> * id — unique web session ID
> * mb_used — data volume used during the session (in megabytes)
> * session_date — session date
> * user_id — user ID
>
> #### Table plans (phone plan data):
> * plan_name — plan name
> * usd_monthly_fee — monthly fee in US dollars
> * minutes_included — monthly call minutes allocation
> * messages_included — monthly SMS allocation
> * mb_per_month_included — monthly data volume allocation (in megabytes)
> * usd_per_minute — price per minute if exceeding the plan allocation (e.g., if the plan has an allocation of 100 minutes, usage from minute 101 onwards will be charged)
> * usd_per_message — price per SMS if exceeding the plan allocation
> * usd_per_gb — price per additional gigabyte of data if exceeding the plan allocation (1 GB = 1024 megabytes)

### Introduction
Megaline company operates in the telecommunications sector. Megaline offers clients two types of prepaid packages: the Surf package and the Ultimate package. This report is aimed at the advertising department, which wants to determine which package is more profitable so they can allocate their advertising budget accordingly.

### Goal
we are use the data to behavior and determine which prepaid package is more profitable and test 2 hypotheses:
* Examining the difference in average revenue between the two prepaid packages.
* Determining whether the average revenue of prepaid packages in the NY-NJ area differs from the revenue in other regions.

### Stages
This project broadly goes through several stages: 
* preparing data
* exploring data
* cleaning data
* analyzing data
* and testing hypotheses

