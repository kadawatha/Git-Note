# Git-Note

#### circle change

<ol> 
 <li>  checkout commit id and create new branch (ex : circle-change)</li>
 <li>  working new fearure in circle-change branch and commit files </li>
 <li>  switch to master branch and continue changing and commit files </li>
 <li>  now we need to merge our circle-change , do merge into current  </li>
 <li>  now we need don't need to cicle branch any more , we can delete  circle-change branch  </li>
</ol>



</hr>

bitbucket push

```

 git push --set-upstream https://kadawatha@bitbucket.org/kadawatha/test-again.git master

```






    git add -A



```

git add README.md

```

<hr>

```

git status

```


<hr>

```

git commit -m "first file in demo repo"

```

<hr>

```

ls -al

```


**git account register**

    git --version
    git config --global user.name "something"
    git config --global user.name
    git config --global user.email "example@gmail.com"
    git config --global user.email
    git config --global --list


**Git branch rename**

<p> Checkout you need branch   </p>

<p> git branch (you will see new branch name) </p>

<p> Put to new branch name   </p>

`git branch -m new-branch-name`

<p> Change old branch name to new branch name   </p>

`git push origin :old_branch_name new_branch_name`

<p> (example - : git push origin :v0_1_O v0_2_0)  </p>
