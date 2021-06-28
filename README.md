# Git-Note

#### circle change

<ol> 
 <li>  checkout commit id and create new branch (ex : circle-change)</li>
 <li>  working new fearure in circle-change branch and commit files </li>
 <li>  switch to master branch and continue changing and commit files </li>
 <li>  now we need to merge our circle-change branch to master branch , do merge into current  </li>
 <li>  now we need don't need to cicle branch any more , we can delete  circle-change branch  </li>
</ol>

#### rebase changes

<ol>
  <li> checkout commit id and create new branch (rebase branch) </li>
  <li> do commit in new rebase branch </li>
  <li> checkout master branch </li>
  <li> go to rebase branch and do rebase into current </li>
  <li> now we don't need rebase branch , delete rebase branch</li>
</ol>


#### merge into specific commit

<ol>
  <li> checkout commit and create a new branch(changes) </li>
  <li> do commit in changes branch </li>
  <li> checkout spacific commit and create new branch </li>
  <li> go to changes branch and merge into current </li>
  <li> checkout master branch last commit </li>
  <li> go to merge commit and , do merge into current  </li>
</ol>


</hr>


how to add image

```
![ajaxcrud](docs/theme.JPG)

```



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




-----------------------------


</hr>

</hr>



redshift ubuntu -O 3000


sudo systemctl stop nginx



sudo systemctl start docker

sudo systemctl status docker

sudo systemctl enable docker

sudo docker ps

sudo docker run -p 3000:80 nginx

http://localhost:3000/

sudo docker ps -a

sudo docker pause fe1f71042611

sudo docker rm fe1f71042611

sudo docker stop f76486678b29



--------------------------


Assign Ownership to the Docker Unix Socket


```

sudo ls -la /var/run/docker.sock

```

```
sudo chown dhanushka:docker /var/run/docker.sock

```


















