# Project-1

**Billboard Charting Artists with RIAA Certifications**
![riaa image](images/riaapic.jpg)

**Project Description**:

This project investigates trends in top billboard charting artists from July 1999 to July 2019 in order to help define and predict possible success factors for record labels and emerging artists.


**Project Team Members**:

Ruth Ashaolu, Kieran Taylor, Sarah Peterson, PJ Gill, and Nicole Bustamante

**Description of data**:
our data was obtained from: https://www.kaggle.com/datasets/danield2255/data-on-songs-from-billboard-19992019

- artistDf.csv: 
"Data on tenured Billboard artists who appeared on billboard between July 1999 and July 2019, released at least 3 albums, and released their first album no later than 2012. These are artists to be considered tenured popular artists. The file has demographic, genre, and history data on them"

- riaaAlbumCerts_1999-2019.csv:
"RIAA certifications given to albums released between July 1999 and July 2019"

**Research Questions**:

    1. Who are the 5 most followed artists on Spotify?
    
![top5spotify](images/top5spotify.png)
![top5spotify](images/followersartists.png)


    2. What Artist has the most albums?
![artistmostalb](images/topartist(gucci).png)

    3. Which Artist released the first album?
![artist to first release an album](images/artistmostalb.png)

    4. Female/male artists – break down number of albums by gender?
![femalevmaleartists](images/mvf.png)

    5. Group/solo  – break down
![groupvsolo](images/groupvsolo.png)

    6a. Summary statistics for followers and number of albums
![summary stats for followers and albums](images/followers%20stats.png)
![summary stats for followers and albums](images/albums%20stats.png)
    
    6b. Statistics for correlations and linear regression:
correlation and regression for number of albums and followers
![summary stats for followers and albums](images/followersalbscatter.png)
correlation and regression for number of albums and years since first album
![summary stats for followers and albums](images/yrsalbscatter.png)

    6c. Statistics for which artists produced most albums per year
![most albums per yr](images/albpryrtop5.png)


    7. What Label generated the most albums?
![labels most albums](images/lblmostalb.png)

    8. Which Artists have achieved Diamond status?
![diamond artists](images/diamond%20artist.png)

    9. Which Labels have achieved Diamond status?
![diamond labels](images/diamond%20label.png)

    10. Which Artists have acheived Platinum status?
![plat labels](images/plat%20artist.png)

    10. Which Labels have acheived Platinum status?
![plat labels](images/label%20plaat.png)

    10. Which Artists have acheived Gold status?
![plat labels](images/artists%20gold.png)


    11. Which Labels have achieved Gold status?
![gold labels](images/labels%20gold.png)

    12. Which Labels have achieved all 3 statuses?
![all labels](images/lballcerts.png)
(Breakdown by Label and Certification)
![breakdown labels](images/sortedbytotal-dia.png)

    13. What were the most popular Genres?
![genres](images/top%20genres.png)

**Final Summary and Analysis**:

After looking at general trends in the data sets and addressing our research questions, we found that there are several factors that may help predict the success of artists and record labels. Our analysis helped us identify artists who showed overall success in their careers and may therefore be role models for up and coming musicians. Ed Sheeran was the most followed artist on spotify, Gucci Mane produced the most albums, and Gene Autry released the first album in the dataset in 1929. Gucci Mane also has put out the most albums per year since the year of his first album.

Some overall trends in this data set indicate that the music industry is predominantly male solo artists. In terms of genre, ‘dance pop’ and ‘rap pop’ were the two most popular categories. The average number of albums artists put out was 11.3 and average number of followers was 1838602. There was weak positive correlation between number of albums and followers, but there was a stronger positive correlation between number of albums and years since first album. This may indicate that the longer an artist has been putting out albums, the more albums they generate which could contribute to greater sales and success. 

The data illustrates that being signed to more prominent, long-standing record labels can be a defining factor of success for emerging artists. Record labels who produced more albums also received more certifications (diamond, platinum, gold). Columbia put out the most albums. Certifications may also indicate success for artists and labels. The top artist achieving Diamond was Shakira and the top label was Sony Latin. The top achieving artist for Platinum was Kenny Chesney and the label was Columbia. The top artist achieving Gold was Elvis Presley and the label was again, Columbia. Columbia by far received the most certifications for Diamond, Platinum, and Gold. The multibar chart is further breaks down the certifications for each label. 
















