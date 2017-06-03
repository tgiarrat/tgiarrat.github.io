## Daily Hub Application
 **_By Thomas Giarratana_**

### Overview

This app is intended to put all of the information that i check daily into one simple to use place. Currently, the basic idea behind the app works. The user is able to view weather and thier preferred selection of news sources. However, I was unable to meet my original scope where I hoped for charts, stocks, and possibly grades to be present. While I wasnt able to meet my intended scope I feel what the functionality that is present works basically as I envisioned it.

### Details

**Functionality**: 
- View weather and News
- Change Location of weather data
- Edit preferred News Sources
- I am in the middle of getting filtering for articles implemented but have not yet completed work on that. 

**Design**
- The strategy pattern is used with Fetch where the different strategies are the different apis that I am useing
- The singleton pattern is used with SourceSelection where only one class is needed for it

### Basic Application Flow
- When the user first opens the application they will only see the default weather card (San Luis Obispo) 

![Alt Text](/305AppScans/Capture.PNG?raw=true)

- To change weather location navigate to the options menu in the top right

![Alt Text](/305AppScans/Capture2.PNG?raw=true)![Alt Text](/305AppScans/Capture3.PNG?raw=true) 

- to change your preferred news sources navigate to the options menu again

![Alt Text](/305AppScans/Capture4.PNG?raw=true) ![Alt Text](/305AppScans/Capture5.PNG?raw=true)

- To remove news sources (for now) simply select the x on each of the news cards

![Alt Text](/305AppScans/Capture6.PNG?raw=true)

### Current Class Diagram

![Alt Text](https://tgiarrat.github.io/305AppScans/diagram.png)


### Thoughts

If I were to go back in time I would probably just slap myself for deciding to focus on android development for tihs class. With all of the stuff we already had to learn and use for this class, learning android on top of that was a bad bad idea. I focused too much time on getting basic android stuff working and little consideration  was then put into design (I ended up going with whatever barely working cobbled togethere solution I could make). 



