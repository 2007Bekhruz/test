# Git guide

# If new PC
1. git config --global user.name "username"
2. git config --global user.email johndoe@example.com
3. git config --list --show-origin(checking)

# If not new PC
1. git init - (создание репозитории для git)
2. create README.md
3. create .gitignore
4. git add .
5. git commit -m "v-1"
6. git branch -M master
7. git remote add origin https://github.com/2007Bekhruz/test.git
8. git push -u origin master

# If project was uploaded
1. git add .
2. git commit -m "comment"
3. git push