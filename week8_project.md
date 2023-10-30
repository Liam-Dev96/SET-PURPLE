# Project work 1


## Summary of issue

This week I returned to the previous issue [Equipment Types](https://github.com/xinjoonha/SET09102_PURPLE/issues/11) to update the codes functionality, update CRUD functions and to  
introduce a repository pattern as each issue has a different model, there is a lot of code repetition. This repetion violates the  
DRY(Don't Repeat Yourself) Principle as with each model  comes a set of CRUD functions from other issues. The repository pattern  
will stop this from happeneing.  
&nbsp;  
The repository was pulled from [PR#51](https://github.com/xinjoonha/SET09102_PURPLE/pull/51) as a collegue already created the repository pattern it just needed implemented and CRUD  
updated to fit this pattern  
&nbsp;  
In figure 1.  you'll see the interface that has all required CRUD methods. The T stands as a general token reciever of a class type  
so that multiple model objects of different type can be accepted


  <figure>
  <img src="images/week 8/img 5.png" alt="fig1" style="width:100%">
  <figcaption align = "center"><b>*Figure 1</b></figcaption>
  </figure> 


&nbsp; 

Since the project uses an SQLite local database this is how the pattern looks implemented  
First, an interface was created and as can be seen from figure 2 the Equipment Types implements the repositories interface where the CRUD  
functions a located and passes the model class as the token ``` T ```  and gets the name returned.

  <figure>
  <img src="images/week 8/repo interface implementation.png" alt="fig1" style="width:100%">
  <figcaption align = "center"><b>*Figure 2</b></figcaption>
  </figure> 

  &nbsp; 

  After creating the interface its time to implement the repository to connect to the database and retrive the name of the equipment types.

   <figure>
  <img src="images/week 8/Repo Implementation.png" alt="fig1" style="width:100%">
  <figcaption align = "center"><b>*Figure 3</b></figcaption>
  </figure> 

  &nbsp; 


  ## Test  
  Unfortuneately i was unable to produce the appropriate tests to test the methods within the project.  
  The testing that was tried to be implemented was NUnit tests as the team agreed to use this testing framework however I do have knowledge of  
  this testing framework i had difficulty producing the test methods.

  ## Code Review  
  The Reviews on my code showed there were conflicts within the appshell.xaml file this was due to conflicting navigation design.  
  The reviews also state that I have broken standard c# conventions when it comes the code layout and indenting. In figures 4 & 5 you can see  
  the reviews left.

  <figure>
  <img src="images/week 8/img 3.png" alt="fig1" style="width:100%">
  <figcaption align = "center"><b>*Figure 4</b></figcaption>
  </figure> 

  &nbsp; 

  <figure>
  <img src="images/week 8/img 4.png" alt="fig1" style="width:100%">
  <figcaption align = "center"><b>*Figure 5</b></figcaption>
  </figure> 

  &nbsp; 

  The conflict within the Undac.csproj is still currently under investigation as there is no obvious reason for the conflict.  
  &nbsp; 

  ## Reviewing code  
  Upon Reviewing [PR#55](https://github.com/xinjoonha/SET09102_PURPLE/pull/55) which is to recruit pool experts it was found that there were no conflicts or issues with the code it used the repository pattern  
  so the code followed the DRY principle. The code also followed standard c# conventions to a high standard with clear naming conventions, correct  
  formatting and being easily readable.  
  The commenting on the code for documentation was quite good and extensive but brief and informative as can be seen in figure 6.  
    <figure>
  <img src="images/week 8/img 8.png" alt="fig8" style="width:100%">
  <figcaption align = "center"><b>*Figure 6</b></figcaption>
  </figure> 

  &nbsp; 

  ## Reflection  
  This week has been tough as the gap in knowledge between me and the rest of the group due to inexperience has left me having to ask for their help on  
  several occasions to go over the program and what tools i can use to improve my learning, however, i have learned quite a lot this week and been able  
  close the gap a little. The reasoning for not being able to produce the test methods are that between catching up on the programming language and using  
  frameworks that i have never used before and trying to complete the tasks everyweek there was simply not enough time to complete the test environment.    
  &nbsp;  
  As for teamwork the team have engaged more this week than ever the team have about 5 or 6 people that have extra knowledge and are using it to better  
  the workflow but the team are far from perfect however they seem to have been more organsied than ever.  
  &nbsp;  
  I believe the group as a whole myself included are not advancing enough within the project but I think this has to do with lack of knowledge in the same  
  areas as myself and the stress of having to try and keep up has them disheartened and therefore less engaged.