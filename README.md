# Practice №1  

---
## command line

Cd <dir> #parent directory 
Ls  “List directory Contents”  
Ls -a #extended list   
Pwd  “print working directory”  
Touch #create new file  
Mkdir <directory> #create dir  
Mkdir -p <> #create cascade of directories  
Cp <what><what>  <where> “copy”  
Mv <what><what> <where> “move”  
Cat “conCATenate and print” #textOnly  
Rm, Rmdir “remove”  
Rm -r <> “remove with recurse”  
---
git config —global user.name “name”  
git init   
rm -rf  .git (r-recursion, f-forced)   
git add (—all) #ready  
git commit  -m “commit name”  #go  
git commit —amend —no-edit #amendSmth  
git log #historyOfCommits  
git log —oneline  
git reset —hard <hash> reset to commit  
git restore <file> #return to last commit  
git restore —staged <file> (staged->untracked)  
git diff #seeTheDifference(last)  
git diff —staged  
git diff <hash> <hash>  

git cat-file -p #seeWhatInHash  


git remote add origin <ssh address> #Tie them  
git remote -v #checkAllOkay  
git remote rm origin  
git push -u origin master  
git push origin master   
git push origin —all  

---

SSH “Secure SHell protocol”  
ssh-keygen -t ed25519 -C “<email>  
ls -a ~/.ssh  
clip < ~/.ssh/id_ed25519.pub  
ssh -T git@github.com  
 
——————-
echo “string” >> file.txt  

—————-
git branch
git checkout/switch <branch>

