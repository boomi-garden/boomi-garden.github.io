SFDC to MYSQL
# Requirements

<img src="./images/20220724203211.png" class="img-right">

- Propsect account types only
- Modified in the last 24 hours
- Does not exist in MYSQL
- Addition to solution:
  - Is account number empty?


<aside class="notes">
<ul>
<li>An area for improvement was found</li>
<li>Check if account number exist in SFDC</li>
<li>If account number is null we send a slack notification to a channel</li>
</ul>
</aside>