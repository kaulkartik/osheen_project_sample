# osheen_project_sample

## Browse to local folders  
* cd {workfolder} 
* mkdir repos  

## how to clone !  
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### clone url. 
* git clone https://github.com/kaulkartik/osheen_project_sample.git
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### knowing your branch  
* git branch 

```bash
➜  osheen_project_sample git:(master) git branch
* master
````
###### uploding the project   
* cp {proj_exiting_dir} {work_dir}

###### reviewing your chnages. 
###### This will give you list of all files in your project  since it is the   first time that you are uploading the project.  
###### After this you will be seeing only the files that have been chnaged from   last time once you run this command second time and so on.  
* git status 
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
 
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
## add the chnages  
###### this adds all the chnages   
###### you may also add selected chnages but  -{option} for that is diffrent   
* git add -A
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### commiting the chnages in the git repo. 
* git commit -m "[ProjectName] [Chnage Number] commit message"

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### pushing the commmits on to the git hub server. 
* git push 
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### now run git status again 
###### This should show a message that there is nothing else to commmit. 
###### since you have uploaded all the chnages on to the server   
* git status 
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### Making new branches  
###### go to git hub account that host your repo   
###### select the branch eg. master branch  
###### select the create new. branch fron here button  
###### make a developement branch   
###### better to keep the running verion of the project on master branch  
###### All inprogress chnages should go on to the devlopment branch   
###### AFTER you are done go to your machine    
* cd {work_dir}
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### fetch all the new created branches in the server   
* git fetch -a
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### checkout the fetched branch     
###### in your case the dev branch    
* git checkout development 
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### check status   
git status 
```bash
➜  osheen_project_sample git:(master) git branch
* master
````
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### if you want sonme one to take your code ask him to do this. 
* git clone <clone url>

* git checkout development 
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### pull the lastest branch. 
* git pull -f 
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★
###### how to review your commits on to your brancch   
###### this gives you one commit message of last 10  commits in your branch. 
* git log --oneline 10
★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★★

## Release Notes. 
###### Pr procedure needs to be explained.  
