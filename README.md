

## **intro-to-git for web development**


 - Part 1 : local folders and files

```sh
     $ mkdir foldername
     $ touch filename.format
     $ nano filename.format
```


 - Part 2 : initialize local repository 

```sh
     $ git init 
     $ git status
     $ git add chapter1.txt // adds to the staging area 
     $ git commit -m "complete chapter1" // adds to repository
```
  
 
- Part 3 : track logs 

```sh
    $ git log 
    $ git diff chapter1.txt // for differences 
    $ checkout chapter3.txt // to turn back to latest version
```

 - Part 4 : push remote repository

```sh
     $ git remote add origin [link of related repo ]
     $ git push -u origin master
```


- additional information

```sh
    $ git rm --cached -r . // remove all from staging area 
    $ git clone  [sample_repository](https://github.com/angelabauer/test-github-pages.git)
```



> Written with [StackEdit](https://stackedit.io/).

> Updated with [Dillinger](https://dillinger.io/).


