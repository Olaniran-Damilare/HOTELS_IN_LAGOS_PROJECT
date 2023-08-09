**XYZ has contacted us to help execute the task below**

OVERVIEW

This data contains data for all hotels in Lagos but our focus is on properties in Victoria Island and ikeja. Kindly assist in determining the TOP 7 hotels based of ratings, cost and likes from the social media survey. Also, determine based on ratings, the top 15 properties both in ikeja and Victoria Island combined. 
We want this dashboard to be interactive and can allow customers make a right choice for their visitations. We would like this dashboard to be visually appealing and simple. 



**SOLUTION**

SELECT DISTINCT Hotel_Name,Likes,Address
FROM Hotels.hotel
WHERE Location='Ikeja'
GROUP BY 1,2,3
ORDER BY 2
DESC
LIMIT'7'
