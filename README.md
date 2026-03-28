git init
    create project

git add .
    add current folder

git commit -m
    commit with message

git push -u origin main
    push with upstream set

git push
    push current branch if have upstream

bit checkout -b
    create brannch and checkout

bit branchs
    list branches

git clone
    clone existing repository

git branch -M main
    rename branch
    
git remote add origin <URL>
    add remote branch

ssh-keygen -t ed25519 -C "san.ok@bk.ru"

ssh-add --apple-use-keychain ~/.ssh/id_ed25519

pbcopy < ~/.ssh/id_ed25519.pub
    add publick key for adding to git