# Setup

This section documents your practical work in week 2.

The main requirements are to show that:

1. Your development environment is correctly set up
2. You understand the setup including potential alternative configuration settings

## Environment configuration

Here, you should include appropriate screenshots with additional commentary. 

**DO**

* Place your image files in the `images` folder
* Choose your screenshots carefully so that they communicate the appropriate information.
  Many screenshots with no clear purpose or with trivial differences are of little value.
* Provide <ins>descriptive</ins> commentary to explain why the screenshot is included. 
  what it shows and point out any particularly significant details.
* Modify your screenshots - for example, by adding arrows, outlines or other highlighting 
  techniques - to enhance their communication value.
* Remove unnecessary material from your screenshots such as toolbars, other windows and 
  computer desktop to eliminate distractions.
* Ensure that any important content is clearly legible. Pay particular attention to text
  size and image resolution.
* Use [numbered captions](https://towardsdev.com/3-ways-to-add-a-caption-to-an-image-using-markdown-f2ca30562be6) 
  as labels for images. Also, use the caption numbers to refer to images in your text.

**DON'T**

* Expect the reader to understand your reasons for including a screenshot. If you can't
  explain it, the screenshot will not do the job on its own.
* Include self-evident comments. For example, don't simply list the values used on a
  configuration page if those values are clearly visible in the screenshot.

## Reflection

For this section, decide what points are worth making and structure your content 
appropriately.

**DO**

* Use sub-headings to differentiate between sections
* Provide <ins>reflective</ins> commentary that discusses, for example, limitations of
  your current configuration, how your configuration is appropriate for the current 
  project, alternative configuration that might be appropriate in ther circumstances, 
  etc.
* Mention any difficulties you had setting up your working environment and how you 
  resolved them

**DON'T**

* Repeat the descriptive commentary from point 1
* Give a blow-by-blow account of everything you did. Instead, you should highlight 
  the important points.   
  
  &nbsp;  
  
# Setting Up the Environment.  
First I installed Visual Studio 2022 Community Edition [here.](https://visualstudio.microsoft.com/vs/)

  <figure>
  <img src="/images/figure%201.png" alt="fig1" style="width:100%">
  <figcaption align = "center"><b>Figure 1.</b></figcaption>
  </figure>  
  
  &nbsp;  
  
  after the installer has downloaded its time to select the workloads for the project.  
  The project will be written in C# using the .NET MAUI framework so that the project  
  is cross-platform.  
  
  <figure>
  <img src="/images/figure%202.png" alt="fig2" style="width:100%">
  <figcaption align = "centre"><b>Figure 2</b></figcaption>  
  </figure>  
  
  &nbsp;  
  
  the group decided on the standard configuration of the git project, the project is set  
  to private so that only approved contributors can make changes, pull and push requests etc.  
  After the project is created to clone the repository to Visual Studio click 'code'.  
  Then copy the repository link.  

  <figure>
  <img src="/images/figure%205.png" alt="fig5" style="width:100%">
  <figcaption align = "centre"><b>Figure 3</b></figcaption>  
  </figure>  
  
  &nbsp;  
  
  Open Visual Studio and click 'Clone Repository' 
  <figure>
  <img src="/images/figure%204.png" alt="fig4" style="width:100%">
  <figcaption align = "centre"><b>Figure 4</b></figcaption>  
  </figure>  
  
  &nbsp;  
  
  Paste the repository link into the text box and hit clone.  
    <figure>
  <img src="/images/figure%206.png" alt="fig6" style="width:100%">
  <figcaption align = "centre"><b>Figure 5</b></figcaption>  
  </figure>  
  
  &nbsp;  

  Git successfully cloned ready for project start.  
  <figure>
  <img src="/images/figure%207.1.png" alt="fig7" style="width:100%">
  <figcaption align = "centre"><b>Figure 6</b></figcaption>  
  </figure>  
  
  &nbsp;  
  
from here i can create the files required from the requirements of the project and update the project on both local server and pushing changes to git.  
  
  &nbsp;  

  # Reflection.  
  The current set up and configuration for this project is needed as this project invloves creating a cross-platform app that will need to be available when internet isn't, this will need a local database to achieve this.  
    
  &nbsp;  

on top of this due to not having used github very much before this project made it a little bit difficult to get set up as visual studio code and its build tools interfered with visual studio 2022 community edition.  
 The cause of the problem was not found, however, uninstalling visual studio code and the build tools and only having visual studio 2022 fixed the issue and the rest of the set up went without any other issues. 
