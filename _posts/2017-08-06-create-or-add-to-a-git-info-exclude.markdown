---
layout:     post
title:      "Create or add to a .git/info/exclude file."
subtitle:   "Adding ignore files"
date:       2017-08-06 17:58:00
author:     "Dony Purnama"
header-img: "img/terminal-osx.jpg"
---

<p>Recently i am learning on GIT, as a web developer i have to deal with git stuff,</p>

<p>At the point i need to use image, sound, attach file and modified some files but those file should not commit to the git server,
as i know just put to .gitignore and then done.</p>

<p>At the moment it's done, but the problem come up, everyone has .gitignore and for the versioning .gitignore should exist.</p>

<p>After browsing i found in <a href="http://Stackoverflow.com">Stackoverflow</a> on this <a href="https://stackoverflow.com/questions/43593697/how-do-i-create-add-to-a-git-info-exclude-file-to-ignore-files-locally>link</a>, the solution is put the path file on files in .git/info/exclude</p>

<h2 class="section-heading">The Final Frontier</h2>

<p>First, you most likely want to use .gitignore instead of .git/info/exclude. It does the same thing, except it gets checked into the repo and versioned along with all the working files. I</p>

<p>just open your terminal</p>

<p>enter into your repo directory</p>

<blockquote>$cd .git</blockquote>

<p>create new directory if doesnt exist</p>

<blockquote>$mkdir info</blockquote>

<p>or open directory if exist</p>

<blockquote>$cd info</blockquote>

<blockquote>$ls</blockquote>

<p>you will see "exclude" just open it with vim editor on your terminal</p>

<blockquote>$vim exclude</blockquote>

<p>after you enter in the file, just press "a", and then will show "INSERT" in the left bottom of editor</p>

<p>you ready to add a path file to ignore</p>

<p>After finish add the script, you can end it or exit to save the changes with</p>

<blockquote>"esc" and then ":"+ "w"+"q" and then enter</blockquote>

<p>and then just commit your changes to the repo</p>

<p>VOILA....... that all</p>

<a href="#">
    <img src="{{ site.baseurl }}/img/git-ignore.jpg" alt="Git Ignore">
</a>
