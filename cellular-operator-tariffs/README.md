# Title
Determination of a favorable tariff for a telecom company

Area: Marketing Analysis, Product Analysis, Data Analysis

Goal of the project: Based on the data of the mobile operator's customers, analyze the behavior of customers and search for the optimal tariff
Project description: A preliminary analysis of the use of tariffs on a sample of customers was carried out, the behavior of customers when using the operator's services was analyzed, and optimal sets of services for users were recommended. The data were preprocessed and analyzed. The hypotheses about the difference in the revenue of subscribers of different tariffs and the difference in the revenue of subscribers from Moscow and other regions were tested.

Data: Data on 500 users of the mobile operator: who they are, where they are from, what tariff they use, how many calls and messages each sent in 2018.

Data description:

Table "users" (information about users):
* *user_id* — unique user ID
* *first_name* — username
* *last_name* — user last name
* *age* — user's age (years)
* *reg_date* — tariff connection date (day, month, year)
* *churn_date* — date when the tariff was discontinued (if * the value is omitted, then the tariff was still valid at the time of uploading data)
* *city* — user's city of residence
* *tariff* — tariff plan name

Table "calls" (information about calls):
* *id* — unique call number
* *call_date* — call date
* *duration* — call duration in minutes
* *user_id* — identifier of the user who made the call

Table "messages" (message information):
* *id* — unique message number
* *message_date* — message date
* *user_id* — identifier of the user who sent the message

Table "internet" (information about Internet sessions):
* *id* — unique session number
* *mb_used* — amount of Internet traffic spent per session (in megabytes)
* *session_date* — internet session date
* *user_id* — user ID

Table "tariffs" (information about tariffs):
* *tariff_name* — tariff name
* *rub_monthly_fee* — monthly subscription fee in rubles
* *minutes_included* — the number of minutes of conversation per month included in the subscription fee
* *messages_included* — number of messages per month included in the subscription fee
* *mb_per_month_included* - the amount of Internet traffic included in the subscription fee (in megabytes)
* *rub_per_minute* - the cost of a minute of conversation in excess of the tariff package (for example, if the tariff includes 100 minutes of conversation per month, then a fee will be charged from 101 minutes)
* *rub_per_message* — the cost of sending a message in excess of the tariff package
* *rub_per_gb* - the cost of an additional gigabyte of Internet traffic in excess of the tariff package (1 gigabyte = 1024 megabytes)

Libraries: Python, Pandas, Matplotlib, NumPy, SciPy

Tags: descriptive statistics, statistical hypothesis testing
