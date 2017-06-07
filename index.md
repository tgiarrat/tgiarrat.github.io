
## Daily Hub Application
 **_By Thomas Giarratana_**

### Overview

**Purpose**
- The idea behind this project is to consolidate useful information from multiple sources that I check fairly often and present each of them well within a single app.

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
    + I ended up producing code that only just worked and did so in a narrow focus and was not layered 
  - To everyones suprise it turns out that a poorly thought out design leads to code that is:
    + More difficult to test
    + More difficult to modify
    + more difficult to understand
    
### Thoughts on the project
  - While I made some mistakes I am still happy with what I have made
    + I still like the idea of putting all these news stories together 
    + I am mostly happy with the simplicity of the application
    + Going through the growing pains of learning android did pay off
      x A lot was learned from my struggles
        - AsyncTask!!!!!!!!
  - Biggest lesson: START EARLY
    + Otherwise you start accumulating technical debt from the start and it just makes your life all around harder.
 

### Current Class Diagram

![Alt Text](https://tgiarrat.github.io/305AppScans/diagram.png)

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



