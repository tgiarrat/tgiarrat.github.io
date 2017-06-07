
## Daily Hub Application
 **_By Thomas Giarratana_**

### Overview

**Purpose**
- The idea behind this project is to consolidate useful information from multiple sources that I check fairly often and present each of them well within a single app.

### Details

**Functionality**: 
  - View weather and News
  - Change Location of weather data
  - Edit preferred News Sources
  - Filtering news stories was only partially completed. I have been able to do the basic logic behind it but have run into many problems
    + To show a simple example of what I was going for I hardcoded an an easy one button filter 

**Design**
  - The strategy pattern is used with Fetch where the different strategies are the different apis that I am useing
  - The singleton pattern is used with SourceSelection where only one class is needed for it
  - Overall, I might serve as a great example of what happens when you dont design very well...
    + Due to a mixture of procrastination and difficulties learning android, I had problems making sufficient progress on code while still maintaining good software quality and correctly implementing design patterns
    + I ended up producing code that only just worked and did so in a narrow focus
    + this resulted in an overall design that was not very modular and difficult to work with 

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



