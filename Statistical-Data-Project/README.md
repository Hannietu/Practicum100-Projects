<ins>Project Description:</ins>
<br> The telecom company Megaline offers its clients two prepaid plans, Surf and Ultimate. 
This project includes a preliminary analysis of the plans based on a relatively small client selection of 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018. </br>

<ins>Description of the data:</ins>
<br><i>The users table (data on users):</br></i>
<br><b>user_id</b> — unique user identifier</br>
<br><b>first_name</b> — user's name</br>
<br><b>last_name</b> — user's last name</br>
<br><b>age</b> — user's age (years)</br>
<br><b>reg_date</b> — subscription date (dd, mm, yy)</br>
<br><b>churn_date</b> — the date the user stopped using the service (if the value is missing, the calling plan was being used when this data was retrieved)</br>
<br><b>city</b> — user's city of residence</br>
<br><b>plan</b> — calling plan name</br>
<br><i>The calls table (data on calls):</br></i>
<br><b>id</b> — unique call identifier</br>
<br><b>call_date</b> — call date</br>
<br><b>duration</b> — call duration (in minutes)</br>
<br><b>user_id</b> — the identifier of the user making the call</br>
<br><i>The messages table (data on texts):</br></i>
<br><b>id</b> — unique text message identifier</br>
<br><b>message_date</b> — text message date</br>
<br><b>user_id</b> — the identifier of the user sending the text</br>
<br><i>The internet table (data on web sessions):</br></i>
<br><b>id</b> — unique session identifier</br>
<br><b>mb_used </b>— the volume of data spent during the session (in megabytes)</br>
<br><b>session_date</b> — web session date</br>
<br><b>user_id</b> — user identifier</br>
<br><i>The plans table (data on the plans):</br></i>
<br><b>plan_name</b> — calling plan name</br>
<br><b>usd_monthly_fee</b> — monthly charge in US dollars</br>
<br><b>minutes_included</b> — monthly minute allowance</br>
<br><b>messages_included</b> — monthly text allowance</br>
<br><b>mb_per_month_included</b> — data volume allowance (in megabytes)</br>
<br><b>usd_per_minute</b> — price per minute after exceeding the package limits (e.g., if the package includes 100 minutes, the 101st minute will be charged)</br>
<br><b>usd_per_message</b> — price per text after exceeding the package limits</br>
<br><b>usd_per_gb</b> — price per extra gigabyte of data after exceeding the package limits (1 GB = 1024 megabytes)</br>

<ins>Project Goal:</ins>
<br>The goal is to analyze clients' behavior and determine which prepaid plan brings in more revenue in order to adjust the commercial department advertising budget.</br>

