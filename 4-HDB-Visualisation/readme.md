## Data Visualisation

### Uncovering trends in HDB resale market

#### *A Visualisation Project*

Visit <a href="https://data.gov.sg/">data.gov.sg</a> to obtain national dataset for exploration, it's a great place to obtain stats as from there as they are generally clean, reliable and valid. As such, there is not much of data wrangling needed, however one still needs to check to ensure the data is consistent when merging datasets from different datasets.

Using the R’s boxplot function, I was able to create charts showing the median resale prices of 3, 4, 5-room and executive flats. Features of a boxplot is summarised as follows:
<br /><br />
*Source: https://r-graph-gallery.com/boxplot.html*
![](boxplot_explain.png)

<br /><br />
A general observation for each flat type is as follows:
<br /><br />
![](3rm.jpeg)
<br /><br />
#### 3-room flats: The value of a 3-room flat declines tremendously once it crosses the twenty-year mark.

<br /><br />
![](4rm.jpeg)
<br /><br />
#### 4-room flats: The resale prices of 4-room flats are more resilient than those of 3-room flats, partly due to their high transaction volume, as this category of flats is a popular choice among buyers.

<br /><br />
![](5rm.jpeg)
<br /><br />
#### 5-room flats: The chart reveals that these flats suffer two dips in resale prices, first after the twelfth year, followed by a second dip after the fifteenth year. Thereafter, the resale prices of 5-room flats increase despite them getting older.

<br /><br />
![](exec.jpeg)
<br /><br />
#### Executive flats: These larger units are rarely built by the HDB and thus are well sought after by families and investors. Despite being relatively old at between 35 and 45 years, executive flats continue to command high resale prices.

I’ll leave it to individuals to interpret these trends, as it's tough to reach a consensus without conducting a thorough survey, so happy hunting if you're diving into the resale market!

<a style="font-weight:bold" href="https://KenYeoKP.github.io">Return to posts and repositories</a>
