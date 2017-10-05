---
layout:     post
title:      "Put your local code to GITHUB Repo"
subtitle:   "Adding an existing project to GitHub using the command line"
date:       2017-08-02 10:58:00
author:     "Dony Purnama"
header-img: "img/post-bg-06.jpg"
---

<p>I code this because i have an assignment how to put a code on your repository</p>

<p>1. Create a new repository on GitHub. To avoid errors, do not initialize the new repository with README, license, or gitignore files. You can add these files after your project has been pushed to GitHub.</p>

<p>2. Open Terminal.</p>

<p>3. Change the current working directory to your local project.</p>

<p>4. Initialize the local directory as a Git repository.
    <blockquote>$ git init</blockquote>
</p>

<p>5. Add the files in your new local repository. This stages them for the first commit.
    <blockquote>
                $ git add .<br/>
                <i># Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.</i>
    </blockquote>
</p>

<p>6. Commit the files that you've staged in your local repository.
    <blockquote>
                $ git commit -m "First commit <br/>
                <i># Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.</i>
    </blockquote>
</p>

<p>7. At the top of your GitHub repository's Quick Setup page, click  to copy the remote repository URL.</p>

<p>8. In Terminal, add the URL for the remote repository where your local repository will be pushed.
    <blockquote>
                $ git remote add origin remote repository URL <br/>
                <i># Sets the new remote</i>
                $ git remove -v <br/>
                <i># Verifies the new remote URL</i>
    </blockquote>
</p>

<p>9. Push the changes in your local repository to GitHub.
    <blockquote>
                $ git push -u origin master<br/>
                <i># Pushes the changes in your local repository up to the remote repository you specified as the origin</i>
    </blockquote>
</p>

<a href="#">
    <img src="{{ site.baseurl }}/img/post-sample-image.jpg" alt="Post Sample Image">
</a>

<p>Placeholder text by <a href="http://spaceipsum.com/">Space Ipsum</a>. Photographs by <a href="https://www.flickr.com/photos/nasacommons/">NASA on The Commons</a>.</p>
