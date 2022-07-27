SFDC to MYSQL
# Requirements

<img src="./images/20220727110644.png" class="img-right">

- Propsect account types only
- Modified in the last 24 hours

<aside class="notes">
<ul>
<li>We then run a condition check to only process records modified in the past 24 hours</li>
<li>We do this by comparing two values</li>
<li>The first is the SFDC last modified field</li>
<li>and the second is a greater than or equal to relative to 1 day ago.</li>
</ul>
</aside>