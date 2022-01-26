<h1>Question</h1>
<p>Query all columns for all American cities in the <strong>CITY</strong> table with populations larger than <code>100000</code>. The <strong>CountryCode</strong> for America is <code>USA</code>. </p>

<p>The <strong>CITY</strong> table is described as follows:  </p>

<p><img src="https://github.com/1erkandogan/HackerRank/blob/main/_IMG_LIBRARY/sql_basic_select_1.jpg" alt="CITY.jpg" title=""></p>

<h1>Solution</h1>
<code>
SELECT *
FROM CITY
WHERE COUNTRYCODE = 'USA' AND POPULATION>100000;
</code>