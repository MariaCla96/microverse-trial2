#Push code into public repository
1. Make sure everything is saved, staged and commited
2. Create repository in Gihub
3. Use git cmd and enter to the folder path
4. Check 'git status' and 'git log --online'
5. Give repository an Alias 'git remote add origin url_of_repository'
6. Use command 'git push origin master'

#Add file to staged
1. Use git cmd and enter to the folder path
2. Check 'git status' and 'git log --online'
3. Write 'git add .'

#Commit all staged files
1. Use git cmd and enter to the folder path
2. Check 'git status' and 'git log --online'
3. Write 'git commit -m log_description'

#Clome repository
1. Use git cmd and enter to the folder path where you want it 
2. Command 'git clone url_of_repository'
3. When push code, there's no need to create alias origin
4. Command 'git push origin master'

#Pull code from origin
1. Use git cmd and enter to the folder path
2. Command 'git pull origin master'

#Creating branches
1. Use git cmd and enter to the folder path
2. Command 'git checkout -b Maria'
3. Check all the branches with 'git branch -a'
4. Now you can add to staged, and commit files here without editing the master
5. Go to github and Pull request
6. The merging will be done in github when eveyone else has checked the new editions
