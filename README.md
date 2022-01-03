# A Web Page Presentation of Bacterial Data Findings

### *Files*:
- [charts](charts.js)
- [index](index.html)
- [style](style.css)
- [samples](samples.json)

## **Deployed Site URL**:
- (https://helyxm.github.io/plotlydeploy/)
- ![dashboard_image](module12_challenge_dashboard)


## **Introduction**:
This project was conducted with the intention of presenting findings on the different bacterial concentrations found in the navel regions of several tested people. The data was collected with the intention of finding bacteria that synthesize proteins capable of producing a similar flavor type to beef. A colleague named Roza was able to provide a collection of sampled data findings and sought a way to present the data in a visually appealing and accessible way through a small collection of chart types. The page, which can be reached from this GitHub repository, presents three charts and a list of demographic details relating to each test subject, with all presented information able to be re-populated with data from each test subject each time a new subject's ID number is selected from the drop-down menu at the top-left section of the page.

## **Analysis**:
This page contains three charts that provide a visual representation of the data findings for each test subject provided in the sampled data sheet from Roza. The charts include:
- A bar chart that displays the top 10 most concentrated bacterial cultures found in that test subject's navel region. This chart provides the Operational Taxonomic Unit for each bacterial culture on the y-axis and provides horizontal bars that represent the concentration values recorded in the data file. When OTU data group's bar is hovered over, the chart provides the listed bacterial names for greater information about the recorded data.
- A gauge chart that provides contextual data on the washing habits each test subject provided about the frequency they each washed their navel regions per week. This information is very useful for providing insight into whether the level of bacterial concentration may be more dependent on the individual's body or if their washing habits may have a greater impact instead. The gauge's bar has a green bar inside that expands to show the recorded frequency number reported and the value is also numerically provided below the chart. The range extends from 0 to 10 times in a week, with 10 being the highest recorded frequency among the sampled data values.
- A bubble chart that provides an overview of the bacterial cultures without the limit placed on these findings in the first chart's data. The circle sizes are dependent on the recorded concentration values and the circles are centered on the coordinates with the y-axis representing the concentration values and the x-axis representing the OTU ID numbers for each bacterial culture. When hovered over, each circle provides a box that shows their respective y-axis values of bacterial concentration and the names of the bacteria found in the culture represented by the OTU ID numbers.

In addition to charts, the page presents demographic information for each test subject including their ID number, ethnicity, gender, age, reported home location, navel or belly button type (concave or convex extension of body tissue), and the reported washing frequency values.

## **Conclusion**:
This project provided the opportunity to carry out an analysis of data through javascript and to present the data in an HTML-constructed webpage that is hosted by a github server instead of requiring local hosting for the page to run. This step has made presenting the data analysis much easier compared to the previous projects involving HTML web page construction and also allows for some great opportunities to customize the way the data is presented based on the preferences of the code's author.
