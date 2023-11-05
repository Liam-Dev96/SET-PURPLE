# Project work 2
## Summary of issue

This week I worked on [Operational Team Status' issue #22](https://github.com/xinjoonha/SET09102_PURPLE/issues/22). The end goal for this issue was to list, create, update and delete reference values for operation team status'.  
 These status' have the available names 'Requested' for when the team has been requested but not yet active. There is the 'Active' name  
that says that a particular team is already active elsewhere. The next is 'Confirmed', this is for the teams that have accepted a mission but not yet at the location on active duty.  
Lastly there is 'Unavailable' for if the team is on leave, off sick or for anything else not accountable for that would make them not be bale to undertake their task.
&nbsp;  
The issue implemented the repository pulled from [PR#51](https://github.com/xinjoonha/SET09102_PURPLE/pull/51) and CRUD functions where created. The Program works but the UI doesn't  
match the CRUD UI template for administrators to have a consistent interface. This problem will be worked on in future updates.
&nbsp;  
In figures 1 & 2 you will see the differences in the UI and how much better the program will be once the template is used.


  <figure>
  <img src="images/week 9/OTS-UI.png" alt="fig1" style="width:100%">
  <figcaption align = "center"><b>*Figure 1</b></figcaption>
  </figure> 

&nbsp; 

  <figure>
  <img src="images/week 9/UI-Template.png" alt="fig1" style="width:100%">
  <figcaption align = "center"><b>*Figure 2</b></figcaption>
  </figure> 

  &nbsp; 

Looking at Figure 1. The simple UI I Created,  
 and Figure 2. The template that was created by a collegue looks much nicer and has more validation for inputs  
 also the buttons fit nicely and are easily readable.
  &nbsp; 

  ## Test  
  Again i was unable to produce the appropriate tests to test the methods within the project.  
  The testing that was tried to be implemented was NUnit tests as the team agreed to use this testing framework however I do have knowledge of  
  this testing framework i had difficulty producing the test methods.  
  If all goes well tests can run as of next week

  ## Code Review  
At this time my code has not yet been reviewed but I believe that the Standard C# Conventions were followed and the program was built with SOLID  
 design principles in mind primarily the single use principle.

  ## Reviewing code  
This week due to time constraints I was only able to review 1 pull request. It was [PR #86](https://github.com/xinjoonha/SET09102_PURPLE/pull/86) which stemmed from [Issue #74](https://github.com/xinjoonha/SET09102_PURPLE/issues/74). The review went well, there  
 were no major issues with the code, no code smells and followed the Standard C# Conventions. The only thing that could do with a cleanup was that there  
 were a few lines that had unneccessary empty lines.
    <figure>
  <img src="images/week 9/OTS-Review.png" alt="fig8" style="width:100%">
  <figcaption align = "center"><b>*Figure 6</b></figcaption>
  </figure> 
&nbsp; 

  ## Reflection  
This week I haven't progressed as far as I would have liked but I still believe I have done a good job considering I am still learning a new language  
I feel that I can actually contribute to tasks now however its not all great as i am still struggling to write the tests for my code which is really  
important as I cant test the limits of my program this will hopefully change by next week.
&nbsp;  
  As for teamwork the team have engaged this week but there has been less engagement when it comes to the code reviews, i think this comes from that there  
  isn't any standard template for reviews. I have proposed a template but still waiting on a response from a few members of the team if they agree or not
&nbsp;  
  I do still believe the group as a whole myself included are not advancing enough within the project, we are advancing its just still really disorganised.  
  There is a genuine struggle to get enough reviews done to make more headway than we have already achieved but i think personal lives have caused a lack  
  of sufficient time this week. 