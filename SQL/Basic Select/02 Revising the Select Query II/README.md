<h1>Question</h1>
<p>Query the <strong>NAME</strong> field for all American cities in the <strong>CITY</strong> table with populations larger than <code>120000</code>. The <em>CountryCode</em> for America is <code>USA</code>. </p>

<p>The <strong>CITY</strong> table is described as follows: <br>
<img src="https://github.com/1erkandogan/HackerRank/blob/main/_IMG_LIBRARY/sql_basic_select_2.jpg" alt="CITY.jpg" title=""></p></div></div>

<h1>Solution</h1>
<code>
SELECT NAME
FROM CITY
WHERE COUNTRYCODE = 'USA' AND POPULATION>120000;
</code>