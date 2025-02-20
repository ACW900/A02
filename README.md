# A02
<p>Alex Wiemer</p><br>

<h1>Step 1: (Github)</h1>
<ol>
<li>Create a GitHub account. (If you dont have one) You can do this at  <a href = "https://github.com/">https://github.com/</a>. Then sign into the account. </li>
<li>Create a new repository by clicking on the + in the rop right corner. Then enter a name for the repository and add a ReadMe file (That is optional but it does make the next steps easier). Then you can click Create Repository.       </li>
<li>After creating this copy the Https link. If you created a ReadMe it will be a green button labeled <>Code and copy the link. (If No ReadMe, the link will be in a blue tinted box Labeled Quick setup) </li>
</ol>

<h1>Step 2: (VS Code)</h1>
<ol>
<li>First Open VisioStudio Code or install at <a href = "https://code.visualstudio.com/">visualstudio.com</a>.</li>  
<li>Next open the file of your desired upload. Then open terminal, either by clicking teriminal at the top of the screen or press Ctrl and +. </li>
<li> Then run the command git init (This makes a New Git folder within your project folder)</li>
<li> Then run the command git add . (It preps all of the project files to transfer to the Git folder we just made)</li>
<li> Then run the command git commit -m "Initial commit" (This is the initial transfer of the files inti the Git folder)</li>

</ol>
<h1>Step 3: (Create the link between)</h1>
<ol>
<li>Next while still in the terminal, run the command git remote add origin <em>(link from step 1)</em>  (This links your project to )</li>
<li>Then run the command git remote -v (This just makes sure your file linked to the Repository) You should get 2 outputs that read as origin <em>(link from step 1)</em>(fetch) and origin <em>(link from step 1)</em>(push)</li>
</ol>

<h1>Step 4: (Final Push)</h1>
<ol>
<li>Next while still in the terminal, run the command git branch -M main (Names newest branch to main)</li>
<li>Then run the command git push -u origin main   (Uploads code to Github)</li>
<li>Finally check your repository on github after refreshing the page.  </li>
</ol>

<h4>Glossary</h4>
<ul>
    <li><strong>Branch</strong>: A current copy of the code that is seperate from the original build.   </li>
    <li><strong>Clone</strong>: A copy of a repository   </li>
    <li><strong>Commit</strong>: The current copy of the build made in your system.   </li>
    <li><strong>Fetch</strong>: Pulls updates from a repository but doesn't merge with your current branch.   </li>
    <li><strong>GIT</strong>: A software for tracing version updates made within your developement tool.  </li>
    <li><strong>Github</strong>: A platform for uploading versions of code that is connected to a communiuty of developers.   </li>
    <li><strong>Merge</strong>: Combines changes made in multiple branches and condenses them into one.   </li>
    <li><strong>Merge Conflict</strong>: Occurs when changes from different branches conflict, this must be fixed manually.   </li>
    <li><strong>Push</strong>: Sending your committed changes to the remote repository.   </li>
    <li><strong>Pull</strong>: Taking changes from a remote repository and merging them into your local branch.   </li>
    <li><strong>Remote</strong>: A version of a repository hosted on a server that you can interact with using Git.   </li>
    <li><strong>Repository</strong>: A storage location for your project's files and the entire history of its changes.   </li>
</ul>
