
## Roasty Toasty
 **_By Thomas Giarratana_**

### Overview

**Ide**
- The idea behind my project was to create a cozy scene where the user roasts AND toasts marshmallows by a campfire. 

**Features of the project**: 
  - Model a fire using particles
  - First person view of a marshmallow on a stick that follows the cameras movements
  - Changing the texture of the marshmallow over time as it gets roasted
  - Camera movement
  - Textured objects
  - Skybox
  
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

![Alt Text](/305AppScans/NewCapture.PNG?raw=true)

- To change weather location navigate to the options menu in the top right

![Alt Text](/305AppScans/NewCapture2.PNG?raw=true)

- to change your preferred news sources navigate to the options menu again

![Alt Text](/305AppScans/NewCapture4.PNG?raw=true) ![Alt Text](/305AppScans/NewCapture5.PNG?raw=true)

- To remove news sources (for now) simply select the x on each of the news cards

![Alt Text](/305AppScans/NewCapture6.PNG?raw=true)







