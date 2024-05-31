<h1 align="left"> Full-Stack-assignment-2-git </h1>

<h1 align="left"> Git Branching, Merging, and Issue Hendiling assignment</h1>
<h2 align="left"> Instructions: </h2>


<h3 align="left"> Part-1: Initial Setup </h3><ul><p><br> 1. Fork this Repository: </br><br> 2. Clone the Repository:</br></p></ul>
<ul>
  <li>&nbsp;Clone the froked repository to your local machine.</li>
</ul>

<h3 align= "left" >Part-2: Create a Feature Branch</h3>

  <br> 3. Create a new Branch </rb>
  <ul>
  <li> Create and switch to a new Branch named feature/added-learning.</li>
</ul>
<br> 4. Create and update a Readme: </br>
<ul>
  <li>Create the learning.cmt file and add a section titled "5 Things I have learned
   <br> about Git and GitHub" with a brief description.</br></li>
</ul>
<br>5. Commit the Changes: </br>
<ul>
  <li>
   add, commit, and push your changes to the remote repository.
  </li>
  <br>git add learning.cmt</br>
  <br>git commit -m "add Project Overview section to learning.cmt" </br>
  <br>git push origin feature/added-learnings</br>
  
    
</ul>
<h3 align= "left"> Part-3: Create an Issue and add few more features".</h3>
<ul>
<br>6. Create an Issue: </br>
<li> On GitHub, create an issue titled " 2 more things I have learnt.</li>
<br> 7. Create another feature Branch:</br>
</ul>
  <ul>
  <li> Create and switch to a new branch named feature/new-learnings.</li>
</ul>
<br>8. Add the new feature: </br>
<ul>
  <li>
    In the learning.cmt file, add 2 more of your learnings.
  </li>
</ul>
<br> 9. Commit the feature Branch </br>
<ul>
  <li>
    Add commit, and pusg your changes to the remote repository.
  </li>
  <br>git add learning.cmt</br>
  <br>git commit -m " added 2 more feature in README"</br>
  <br>git push origin feature/new-learning.</br>
</ul>
<br>10. Close the Issue</br>
<ul>
  <li> Go to GitHub and close the issue " 2 more things I have learnt"</li>
</ul>
<h3 align= "left" > Part-4: Merge Branches</h3>
<br> 11. Merge the feature Branch. </br>
<ul>
  <li>
   Switch to the main branch and merge the feature/added-learning branch.
  </li>
  git checker main 
  git pull origin main 
  git merge feature/added-learnings
</ul>
<br> 12. Merge the new feature Branch</br>
<Ul>
  <li>
    Merge the feature/new-learning branch into the main branch. If there are any conflicts, resolve them.
    
  </li>
 <mark>git merge feature/new-learning</mark>
</Ul>
