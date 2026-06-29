##### 紀錄本機名稱和mail
git config --global user.name "IS-Brian-Li"
git config --global user.email "brian.li@intrising.com.tw"

##### 設定主branch名稱
git config --global core.editor "code --wait"
git config --global init.defaultBranch main

##### 確認設定內容
git config --list

##### add commit
commit -m
feat     # New feature
fix      # Bug fix
docs     # Documentation
style    # Formatting
refactor # Code refactoring
test     # Testing
chore    # Maintenance