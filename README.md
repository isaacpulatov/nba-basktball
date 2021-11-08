# nba-basktball

This is a project in which I compare the NCAA statistics, of players drafted between 2000-2010, of those did make allstar teams versus those who did not.

The college stats for those who did and did not make allstar teams, is in Yes-All-Star.csv and Non-All-Star.csv, respectively.

This is a full-cycle data analysis project, including
<br> (1) data extraction, off of basketball-reference.com and sports-reference.com,
<br> (2) data validation, to make sure I was getting the right player's statistics,
<br> (3) data cleaning, especially when cleaning names to search for player data, and
<br> (4) data visualization, to compare the college stats for both groups of players.

In summary, I extracted, validated, and cleaned the data to visualize the following results:

![image](https://user-images.githubusercontent.com/74286542/140826540-04b503bb-1ddf-42e3-9369-a1de3bf3e9d5.png)
![image](https://user-images.githubusercontent.com/74286542/140826565-87df09f1-caa7-4267-a99a-bfd80939ea7d.png)
![image](https://user-images.githubusercontent.com/74286542/140826594-c13b8c8c-26fe-4bcc-976e-c469cd7c64ec.png)
![image](https://user-images.githubusercontent.com/74286542/140826606-1ce82657-e37f-47e6-a1d2-22595399338f.png)
![image](https://user-images.githubusercontent.com/74286542/140826615-97ae3dbf-5f04-4d27-be47-5e00c82ab1ba.png)

In conclusion:
<br>(1) The difference between allstars and others is not very noticeable in their raw stats.
<br>(2) Some statistics don't even differ by 1 unit, like Total Rebounds or Assists. Points differ by only 1.3 units.
<br>(3) However, when I plotted the percent differences, the difference of 10-20% across most stats was noticeable.

PostScript:
After reviewing this project, I noticed some errors. For example:
<br> (a) Bobby Jones is in the allstar list, because there was an allstar with the same name, and
<br> (b) Patrick Ewing Jr. is in the list, because he went to the same school as his father.

I'll visit these another time, as part of a more robust data validation process, using name + draft year as a unique identifier.
