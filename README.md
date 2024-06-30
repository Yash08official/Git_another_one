<h2>To make it a git repository you need to type command "git init"  then this will intialize the changes then turn into green color {untracked} </h2>

    <!--command  "git status" -->
    <!-- command "git add ." -->
    <!-- command "git commit -m and msg" -->
     <!-- command  "git branch -m main" -->
      <!-- command "git remote add origin https://github.com/Yash08official/Git_another_one.git" -->
       <!-- command "git push -u origin main" -->

       <!-- -u means i set it as a upstream branch . whenever i push plese go to this branch then we dont want to write  "origin main" again and again . {-u means settings main as my upstream branch} -->

<h2> Understand the concept of branching and merging </h2>

Branching : Creating a new branch, doing a work seperately there and you are not mixing it with main branch

<!-- All the code is seperate -->

Merging : Later on you can fanalized your work you merge all the branches to main branch

Git branch command : --> It will tell what branches i have in this repository.

        The branch we have or we are working it shows in green color

If I want to create a new branch then :

"git checkout -b" name_of_branch

ex: "git checkout -b" feature1

then we moved to new branch "feature1"

now when i do git branch again it will show two branches "main" & "feature1"
and we are on new branch "feature1"

In this "-b" means crating a new branch

so if i want to go to existing branch we put "git checkout main"

so this way we crate multiple branches

now lets create new branch "feature2"

git checkout -b "feature2"

and we are on "feature2" branch

lets add some work in feature2 branch we goto index.html  and write
<!--  <p>Work by feature2</p> -->

then we check the status
"git status"

then i will simply say "git add . "
then git commit -m "added paragraph by feature2 branch"
