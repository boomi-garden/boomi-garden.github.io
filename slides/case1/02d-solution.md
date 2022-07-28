SFDC to MYSQL
# Requirements

<img src="./images/20220727112009.png" class="img-right">

- Propsect account types only
- Modified in the last 24 hours
- Does not exist in MYSQL

<aside class="notes">
<ul>
<li>Now we perform a condition check to see if the customer exists in MYSQL DB</li>
<li>To make this work we have to first create a new unique key in your MYSQL DB called "sforceid"</li>
<li>We then compare the SFDC ID to the sforceid to see if they are equal to one another</li>
</ul>
</aside>