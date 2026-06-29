## practice git commands
# git init-> jb hme kisi folder ko apne repository m daalna ho toh terminal m git init likh do
# after writing git init in terminal "U" WILL BE WRITTEN with file name in right side that U means
# file ke changes ko abhi track nhi kiye ja rha
# agr terminal m git status likhoge toh untracked files likha hua aa jyega terminal m

# agr file ke changes ko track krana h toh
# use command git add with file name in terminal (U WII BE CHANGED TO A)

## to remove the file write git rm --cached<file name>
## write git commit -m "custom msg" in terminal to commit your file or code 
# git commit commond is very imp (iske andr jo bhi msg likhthe h vo hmare repo m show ho tha h)


# git branch -M main (to make our main branch)
# agr ab likhenge hm terimnal m git branch toh (* main) show hoga (ab esi branch m hm commit krenge then push krendenge code ko github repository m)

## write->git remote add origin (destinational url) in terminal iske mtlb yeh h ki hmara jo code/data h vo es destination url m commit hoga
# destionational url yaad krne ki need nhi h 
# terminal m git remote -v likh doge toh push aur fetch dono ke url aa jyenge 

# finally to push the code use commond (git push origin main)
# commit-> changes ko locally save krna (apne pc pe)
# push-> wo locally saved changes ko github pe upload krna
## git config --global user.name "Nayan"
## git config --global user.email "tera@email.com" (jo github pe daala h)
# jb life m pehli baar commit krte h toh ek baar daalna pdtha h 
### git add .  saare file ko add / TRACK krdete h jitni bhi h folder m automatically if you want
# "M" KA MTLB H FILE TRACK HO GYI LEKIN COMMIT  NHI HUA CODE


## git add .-> folder ki saari files automatically track ya add hogyengi repo m 
# ab agr git add . likne ke baad nayi file bna rhe toh vo add nhi hogi

# agr hm git add . use kre toh ab bs hme changes krane ke baad git commit and git push krana h chahe same file ho ya new fie ho
## git branch aur git remote add origin — dono sirf ek baar. Chahe kitni bhi files ho.
# git init bhi bs ek baar aata h
# git status -> hme yeh pta chl jata h ki kitni files trace ya add h repo m

# bs whi commits github pr show honge jo push krenge hm 
# agr hmne commit ko push nhi kiya toh vo locally apne computer pr save hoga github pe nhi
## .gitignore hmne direct github se hi bnai h and vscode m us file ko lane ki liye (git pull origin main) commond ko use kiya h
## agr hme koi specefic file prevent krana h commit krne se repo m toh hm usse gitignore file m daal denge



# merging branches in git
# git branch (branch's name) write this in terminal to make a new branch apart from our main branch ( the new branch which will we crete is a copy of our main branch only)
# ab agr hm terminal m git branch commond likhenge toh hme main branch ke alawa bhi ek aur branch show hogi jo hmmne create ki h
# suppose-> branch name is devloper a
# jb hm git branch likhene toh hme 2 branches show hogi terminal m  (main aur devloper a) but main green se show hogi jiska mtlb yeh h ki abhi hm main m present h aur hmne jo bhi coding kri yeh code m changes kiye, toh devloper a branch m n hokr vo changes main branch m hojyenge jo ki prblm h
# isliye hm terminal m ek command likhenge (git checkout branch name) 
# exm-> git checkout devloper a 
# ab devloper a m present honge hm and ab jo changes honge vo devloper a branch m hi honge jo ki shi h and devloper a green se show hoga terminal m
# phele ke saare changes commit krne ke baad branches switch krni hoti h
# jb hm branch change krlenge tb apna code ya code m changes krana h vo sb krlo
# then use git add file  command then commit the code 
# then again use git checkout command (git checkout main) ab jo hmne code devloper a branch m likha tha vo gyab ho jyenga uss code ko apne main branch m merge krane ke liye
# git commnd-> git merge branch's name
# agr merge krte time koi issue  aagye toh  use(git commit -m "resolve merge conflict") after manually reviewing the file
# then delete the copy of main branch which we have created (devloper a branch) uska command net pe mil jyega anyways it's not neccesory but a good practice
# just type delete local branch on google copy the command use it
# at last push the code to github if you want


# git pull
# agr kisi se direct repo se change kiya h code toh phele us code ko pull kro git pull origin main se then fir changes waghera krke commit and push kro

# git log --oneline — commit history dekhne ke liye (clean format)
# git diff — commit se pehle exactly kya changes hue dekh sakta hai
# refer to github commands pdf also


# agr merge krte time conflict aaye toh:
# step 1: file manually edit karo — VS Code conflict wali jagah highlight karta hai
# <<<<<<< HEAD (main branch ka code)
# ======= (divider)
# >>>>>>> developer-a (incoming branch ka code)
# VS Code m upar buttons aate h: Accept Current Change / Accept Incoming Change / Accept Both Changes
# step 2: git add <file>
# step 3: git commit -m "resolve merge conflict"
# automatically resolve nahi hota — kaunsa code rakhna hai ye tera decision hai


# When to use `git pull`
# 1. Someone else has pushed new code to the repository.
#    → Use `git pull` to get those changes on your local machine.
# 2. You pushed code from another laptop/PC.
#    → Use `git pull` on your current device to sync the latest changes.
# 3. You edited files directly on GitHub (e.g., README.md).
#    → Use `git pull` to bring those changes into your local repository.
# 4. You're working on a team project.
#    → Always `git pull` before starting work to avoid conflicts and stay up to date.