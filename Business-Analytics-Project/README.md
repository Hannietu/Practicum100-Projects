<ins>Project Description:</ins>
<br>This project includes an analysis of Yandex.Afisha data:</br>
<br>1. Server logs with data on Yandex.Afisha visits from June 2017 through May 2018
<br>2. Dump file with all orders for the period
<br>3. Marketing expenses statistics
<br>The analysis focuses on:</br>
<br>1. How people use the product
<br>2. When they start to buy
<br>3. How much money each customer brings
<br>4. When they pay off

<ins>Description of the data:</ins>
<br><i>The visits table (server logs with data on website visits):</i>
<br><b>Uid </b>— user's unique identifier
<br><b>Device</b> — user's device
<br><b>Start Ts</b> — session start date and time
<br><b>End Ts</b> — session end date and time
<br><b>Source Id</b> — identifier of the ad source the user came from
<br>All dates in this table are in YYYY-MM-DD format.</br>
<br><i>The orders table (data on orders):</i>
<br><b>Uid</b> — unique identifier of the user making an order
<br><b>Buy Ts </b>— order date and time
<br><b>Revenue </b>— Yandex.Afisha's revenue from the order</br>
<br><i>The costs table (data on marketing expenses):</i>
<br><b>source_id </b>— ad source identifier
<br><b>dt</b> — date
<br><b>costs </b>— expenses on this ad source on this day

<ins>Project Goal:</ins>
<br>Optimize marketing expenses.
