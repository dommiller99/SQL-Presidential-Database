# SQL-Presidential-Database
Introduction
	The President of the United States is the most powerful individual on the Earth. Out of a nation of 330 million people we have one person who is elected to represent the country and serve as President. The President of the United States has an incredible amount of power and influence on not only the country but also the world. Only 45 gentlemen have served as the President since the year 1789; the first President was George Washington while the current President is Donald Trump. These 45 men have shaped the history of our country and have lead us through some dark and harrowing times. 
	I love politics- I read the news every single day and follow politics avidly. I pay attention to current political and economic events of the United States as well as the world. Out of all political topics Presidential politics has to be the one that interests me the most. I find it fascinating that one individual can be delegated so much power and influence. When I wanted to create a database I had no hesitation about doing one which involved politics. After much thinking and consideration I wanted to create a database in SQL on the United States Presidents. My intention for this project was simple; I wanted to create a detailed and unbiased database about the Presidents. My goal was to provide fact- not fiction. I was not to include any personal bias or commentary; I was not rooting for any one president or any one party. 
	I included only 13 out of 45 Presidents in my SQL database. Why is that? The answer is simple. So many different metrics and figures didn’t start getting recorded until relatively recent (around Truman’s Presidency). This includes various metrics such as GDP, unemployment rates, approval ratings, and job creation. For that reason I chose to only include the last 13 Presidents. I felt that this would make the database detailed, concise, and comprehensive. 
	There is so much information out there on the Presidents. Because of this, I decided to split my database up into three tables. The first one is all about the Presidents. I included information such as their full name, age, party, Vice-President, home state, and more. The second table was the Presidency table- this is where I included information about their time in office. This included information about unemployment rates, GDP rates, Supreme Court appointments, job creation, approval ratings, and more. The final table which I included was all about elections. It included information such as electoral vote, popular vote, voter turnout, and more. 
Findings
	Age is a very important factor to many people when choosing a candidate. All of the 2020 frontrunners are 70 Years Old or above (Donald Trump- 73, Joe Biden- 76, Elizabeth Warren- 70, and Bernie Sanders- 78). For this reason I felt that it was important to include age in my database. All of the 3 oldest Presidents were Republican (Donald Trump (70), Ronald Reagan (69), and George H.W. Bush (64)) while the 3 youngest presidents were Democrats (John F. Kennedy (43), Bill Clinton (46), and Barack Obama (47)). The average age for a Republican President was 63 while the average age for a Democrat was 51. Many of these individuals were very qualified to hold the office. Out of the 13 Presidents five had served as Vice-President before (H.W. Bush, Nixon, Ford, Johnson, Truman). One thing that I was curious about was to see if Governors or Senators get higher approval ratings. Many people feel that being a governor better prepares a candidate due to it being an executive not legislative position. Interestingly enough I found that Senators tend to have slightly higher approval ratings than Governors. The average gubernatorial approval rating is 51% while the average senatorial approval rating is 53%. 
	I had a lot of information in my Presidency Table. Executive Orders are actions taken by a sitting president in order to bypass Congress. The three Presidents with the most executive orders are Harry Truman (907), Dwight Eisenhower (484), and Ronald Reagan (381). Judicial appointments are one of the most influential parts of a President’s legacy. Appointing someone to the Supreme Court means that their decisions affect Americans for decades. I found that the average Republican President gets 3 (2.86) Supreme Court appointments while the average Democratic President gets 2 Supreme Court appointments. 
	Economic data was one of the most important factors in my database; I gathered data on a variety of different metrics. One of the most common questions asked by people is “Which party presides over a better economy?” I looked at three entirely different economic metrics (average GDP rate, average unemployment rate, and average job growth). I found that in all cases Democratic Presidents edge out Republican Presidents. The average GDP Rate for Democratic Presidents is 3.3% while the average for Republicans is 2.74%. The average unemployment rate for Democrats is 5.58% while the average for Republicans is 5.84%. Finally, the average job creation percentage for Democrats is 10.33% while the average for Republicans is 7.23%. I’m not saying that either party is superior to the other- all that I’m saying is that Democratic Presidents tend to preside over stronger and more robust economies. 
	I looked at which Presidents performed best with various aspects of the economy. GDP Rate is the rate at which the Growth Domestic Product of a country changes. 3% and above is considered an economy to be moving at a great pace. The three presidents with the highest GDP Rate were all Democrats. They were Lyndon B. Johnson (5.3%), John F. Kennedy (4.3%), and Bill Clinton (3.9%). I also looked at the average unemployment rate during Presidencies. The unemployment rate should be low but not too low. The presidents with the lowest average unemployment rates are Donald Trump (4.1%), Harry Truman (4.2%), and Lyndon B. Johnson (4.2%) while those with the highest average unemployment rates are Gerald Ford (7.8%), Ronald Reagan (7.5%), and Barack Obama (7.4%). Keep in mind that President Trump has only been in office for about 2.5 years. The unemployment rate has had very little variance. Presidents who served longest (8 years) tend to have unemployment rates which fluctuate far more than Presidents who don’t serve as long. Another very important metric is looking at job growth percentage. The Presidents who added the most jobs were Ronald Reagan (16.5%), Bill Clinton (15.6%), and Harry Truman (13%). 
	Approval ratings were also a very important part of my database. I looked at approval ratings from Gallup Polling. Gallup is a non-partisan pollster which is incredibly reputable. I looked at highs, lows, ranges, and the average. These were incredibly interesting numbers to dive into. The approval rating seeks to find out if Americans approve of the job the President is doing. 
	I wanted to find out if Democrat or Republican Presidents have higher average approval ratings. I found that the average Republican approval rating is 52% while the average Democrat’s is 53% (53.167%). I also looked at individual presidents. I found that the three presidents with the highest average approval rating are John F. Kennedy (D-70%), Dwight Eisenhower (R-65%), and George H.W. Bush (R-61%). Interestingly enough, two of these Presidents are Republican while only one is a Democrat. Keep in mind that President Kennedy served less than three years so his approval rating didn’t fluctuate too much. I observed that Presidents who served two full terms had approval ratings with a lot of variance, thus causing the average approval rating to be lower. I also looked at highs, lows, and ranges. I found that the Presidents with the highest highs were George W. Bush (R- 90%), George H.W. Bush (R- 89%), and Harry Truman (D-87%) while the Presidents with the lowest lows were Harry Truman (D-22%), Richard Nixon (R-24%), and George W. Bush (R-25%). Ranges were also an incredibly important factor that I looked at. I found that the President with the lowest range is Donald Trump (R-11%) while the President with the highest range is George W. Bush (R) with a massive 65% range! President Bush reached his peak in 2001 right after 9/11 with a 90% approval rating. His approval rating plummeted towards the end of the second term when the recession started as well as the war in the Middle East was underway. Presidential approval ratings can fluctuate quite a bit depending on various factors. Overall we can notice that the Presidents with better economies have higher approval ratings. 
	Elections was the final table which I included in my database. I had a variety of information such as voter turnout, popular vote, electoral votes, and more.  I wanted to see which President got the highest voter turnout and which party receives higher voter turnout. Dwight Eisenhower had the highest voter turnout (63.3%) in the 1952 election. The average voter turnout when a Republican wins is 56% (55.9%) while the average voter turnout for a winning Democrat is 56.1% (56.06%). This is incredibly close. I also looked at which President received the most electoral votes and which party receives more electoral votes. Ronald Reagan received the most electoral votes (525) in the 1984 election. Republicans, on average, receive more electoral votes than Democrats. Republicans typically receive 402 (402.1) electoral votes while Democrats receive 354 electoral votes (354.375); I was surprised at how big the difference was. The reason is that Republicans often have massive electoral blowouts (Reagan, Nixon, Eisenhower). The final election metric that I looked at is popular vote. Lyndon B. Johnson is the president with the highest popular vote percentage. He garnered 61.1% of the popular vote in the 1964 Election. Republicans, on average, get more of the popular vote than Democrats. The average Republican popular vote percentage is 52% (52.43%) while the average Democratic Percentage is 51% (50.84). Interestingly enough, the two Presidents who lost the popular vote but won the electoral vote were both Republicans. They are Donald Trump and George W. Bush. 

Acknowledgements
	I would like to thank Professor Duffy for her continued guidance, dedication, and assistance with helping me on this project. Her advice and support was incredibly helpful. 
Works Cited
	I used many different resources for this project. Here they are:
https://millercenter.org/president
https://www.whitehouse.gov/about-the-white-house/first-ladies/
https://www.britannica.com/topic/United-States-Presidential-Election-Results-1788863
https://news.gallup.com/interactives/185273/presidential-job-approval-center.aspx
https://ballotpedia.org/Federal_judicial_appointments_by_president
https://www.thebalance.com/job-creation-by-president-by-number-and-percent-3863218
https://historyinpieces.com/research/us-unemployment-rates-president
https://data.bls.gov/timeseries/lns14000000
https://www.hudson.org/research/12714-economic-growth-by-president
https://www.presidency.ucsb.edu/statistics/data/executive-orders
https://www.thoughtco.com/president-during-each-major-war-105471
