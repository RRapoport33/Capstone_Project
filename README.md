Birthing Locations in the US: An In Depth Look Into Freestanding Birth Centers and Hospitals 2010-2020

Motivation:
When I moved to Cleveland, OH I was surprised at the lack of alternate birth options to hospital births. I had coached a friend through two beautiful natural births in a small birth center and had dreams that when it was my turn, I would also birth in the comfort of a not hospital yet safe place.
When I became pregnant with my first child, I looked into other options rather than birthing in a hospital but was dismayed that those options did not exist in Cleveland. I searched out midwives and doulas and ended up choosing to do a homebirth for my oldest daughter.
Since then, I have been interested to see the differences between birthing in a hospital setting versus birthing in a free standing birth center. For this project, I looked at the average APGAR score and whether there had been any or no complications during labor or birth in order to determine whether outcomes were better in the hospital or birth center. I was also interested to see how the number of births over time changed when looking at Mother's Age as well as Mother's Education level. Lastly, I wanted to see the breakdown of what type of mother's were choosing free standing birth center's over hospitals.

Technologies: In order to assess and clean the data, I used Python 3 within a Jupyter Notebook. The data was imported in CSV form so I used Python in order to append and do some cleaning before importing the data into its final CSV. I used Tableau to do the analyzing and charting.

Challenges
-Retrieving the data
  The data that I chose to use was in the form of zipped csv files, in order to make it usable, I needed to unzip the file and choose a number of columns in order for the data to be more usable. As stated before I used Python in order to bring in the CSV using only certain columns. One of the hurdles I ran into was data types not being the same across years, and therefore needing to do some conversion so I was able to analyze across all 10 years. One of the biggest hurdles was knowing that my data would be a bit skewed given the following factors:
  -not all women have access to birth centers (location, payment coverage etc....)
  -birth center's typically only deliver women considered "low risk" and with a maximum age of 35
  -some women cannot birth naturally and therefore need to be in a hospital setting
-Link to Dashboard
