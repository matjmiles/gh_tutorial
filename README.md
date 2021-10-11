# GitHub and GitHub Desktop Tutorial

### <a href="https://youtu.be/dWWZtKjGTgU" target="_blank">Video Tutorial</a>

* <a href="#create-github-account">Create a GitHub Account</a>
* <a href="#create-repository">Create a Repository</a>
* <a href="#install-desktop">Install GitHub Desktop</a>
* <a href="#create-dev-branch">Create A Development Branch</a>
* <a href="#pull-request">Make a Change to the READEME.md file and Create a Pull Request</a>


### <a id="user-content-create-github-account" class="anchor" aria-hidden="true" href="#create-github-account"></a>Create GitHub Account
1. Go to <a href="https://github.com" target="_blank">Github website (right click on this link to open in new window)</a> and click on "Pricing and signup"

![go to gibhub](images/gh1.png)

2. Enter your email address and click continue.

![add_email](images/gh2.png)

3. Create a password and click continue.

![create_password](images/gh3.png)

4. Solve the puzzle to continue.

![solve_puzzle](images/gh4.png)

5. Click "Create account".

![create_account](images/gh5.png)

6. Click "Just me" and "Student" then click "Continue".

![kust_me](images/gh6.png)

7. Click the checkboxes for "Collaborative coding" and "Automation and CI/CD" and continue.

![click_checkboxes](images/gh8.png)

8. Click "Continue for free".

![continue_for_free](images/gh9.png)

### <a id="user-content-create-create-repository" class="anchor" aria-hidden="true" href="#create-create-repository"></a>Create Repository

9. Click "Create repository".

![create_repository](images/gh10.png)

10. Select "Public" or "Private" ad a README file and if you want select a license and click "Create repository".

![public_or_private](images/gh11.png)

11. You should you now be able to see the README.md file.

### <a id="user-content-install-desktop" class="anchor" aria-hidden="true" href="#install-desktop"></a>Install GitHub Desktop

![install_desktop](images/gh12.png)

12. Go to <a href="https://desktop.github.com" target="_blank">GitHub desktop (right click on this link to open in new window)</a> and click on "Download for Windows (64bit)"

![download_software](images/gh13.png)

13. Click the download button for the computer platform you are installing on.

![download_correct_platform](images/gh14.png)

14. Click the GitHubDesktop install executable.

![install_exe](images/gh15.png)

15. The software installation begins and will launch once completed.

![launch_install](images/gh16.png)

16. Select your repository you created in GitHub and click "Clone".

![clone](images/gh17.png)

### <a id="user-content-create-dev-branch" class="anchor" aria-hidden="true" href="#create-dev-branch"></a>Create development Branch


17. Select the GitHub.com tab, select your repository, choose your location and click "Clone".

![clone_repository](images/gh18.png)

18. One of the advantages of using GitHub is the ability to create branches or copies of your project while you are making
 changes. By default a "<strong>main</strong>" branch is created when you add a GitHub repository. You can create additional branches 
like a "<strong>dev</strong>" or development branch that is a duplicate of your "<strong>main</strong>" branch. 
You then make changes to your "<strong>dev</strong>" branch. 
Once you have reviewed and tested those changes you can <strong>commit</strong>
those changes to the main branch. Let's now create a "<strong>dev</strong>" or development branch. Click on "New branch"

![create_dev_branch](images/gh19.png)

19. Type "dev" for the name and select "Create branch".

![create_branch](images/gh20.png)

20. Type "dev" for the name and select "Create branch".

![dev](images/gh20.png)

21. Click "Publish branch" so that the branch is created on the remote site. GitHub is using Git to create these branches 
locally as well as running all of the other Git commands that GitHub Desktop is built upon. 

![publish_branch](images/gh22.png)

22. Now lets edit or README.MD file by clicking on the "Repository" menu then "Show in Explorer".

![edit_readme](images/gh23.png)

23. The directory where our source files are located is opened.

![open_directory](images/gh25.png)

24. Right click on the REAMDE.md file and select "Edit with Notepad++".

![edit_readme](images/gh26.png)

### <a id="user-content-pull-request" class="anchor" aria-hidden="true" href="#pull-request"></a>Make a Change to the READEME.md file and Create a Pull Request


25. The README.md file is in Markdown format. Markdown is a simplified html format that is the standard for README
files on GitHub. 
<a href="https://www.markdownguide.org/basic-syntax/" target="_blank">Here is a link to the basic syntax for Markdown (right click on this link to open in new window)</a>
Make a few changes and click "save".

![markdown](images/gh27.png)

26. In GitHub Desktop you can see the the file has changed. Yuu can also see the text that was changed and how it was
changed. You can then add a description of your changes. Now click "Commit to dev".

![commit_dev](images/gh28.png)

27. Notice that your current branch is the dev branch you created. By clicking "Push origin" the changes you made to your 
local file will get pushed to GitHub in the cloud.

![push_origin](images/gh29.png)

28. Now that your changes have been pushed to GitHub we can create a pull request. By pushing the "Pull Request" button
you are submitting a request to have your code reviewed and if approved, your changes will be merged from the dev branch
into the main branch.

![pull_request](images/gh30.png)

29. Your GitHub repository is then launched in a web browser. GitHub analyzes your code to see if there are any conflicts
with other pull requests which may have been made by other developers. That is one of the advantages of GitHub. It will
track and manage changes made by multiple developers working on the same code repository. 

![track_changes](images/gh31.png)


30. Notice that the changes you made in your dev environment will be merged into your main branch. Click "Create pull request".

![github signup](images/gh32.png)

31. Click "Confirm merge".

![github signup](images/gh33.png)

32. You can now see that the merge was successfully completed. If you want you can delete your dev branch. However, if you
are going to continue working on your project it's probably best to not delete the dev branch.

![github signup](images/gh34.png)







