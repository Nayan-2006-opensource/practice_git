## practice git commands
# git init-> jb hme kisi folder ko apne repository m daalna ho toh terminal m git init likh do
# after writing git init in terminal "U" WILL BE WRITTEN with file name in right side that U means
# file ke changes ko abhi track nhi kiye ja rha
# agr terminal m git status likhoge toh untracked files likha hua aa jyega terminal m

# agr file ke changes ko track krana h toh
# use command git add with file name in terminal (U WII BE CHANGED TO A)

## to remove the file write git rn --cached<file name>
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

