============dvThang124================
- git init
- git status
- echo>led.c# create file led.c
- git add <file>
- git commit -m "..."
- git commit -a -m"..."

- git checkout -b <newbranch> # tạo branch mới và chuyển sang branch đó luôn
- git checkout <branch>  # chuyển sang branch 
- git branch -a/v# list danh sact
- git merge <branchB>    A<-----branchB
- git branch -D <branch># delete branch
- git push --setupstream <remote> <branch_name># push local branch

- git reset --soft id # unbox và đưa về straging area
- git reset --mixed id # unbox và đưa về working directory
- git reset --hard id # xoa luon commit

- git revert id# đảo ngược lại commit và tự tạo thành commit mới
- tạo file .gitignore và điền tên thư mục cần lược bỏ khi commit

- git remote add origin(ten remote) url
- git remote -v
- git remote remove ten remote# delete remote

- git tag -a <tag_name> -m"message" Id
- git tag#show list tag
- git checkout tag_name# switch to tag_name
- git push origin --tags# push all tags
- git tag -d tag_name# delete tag in local
- git push name_remote name_branch/name_tag //git push --force origin master
- git push --delete origin tag_name

- git push origin --delete test #delete branch in remote
- git restore .
- gitk# show flowchart

- git rebase develop