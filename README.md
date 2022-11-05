# Cpsc330 HW 
### How to push your local changes to our repo using terminal commands
1. In terminal, navigate to our repo folder on your local computer
2. Make sure your local is up to date with changes from our repo
'''
git pull
git pull origin main  //for pulling from main branch
'''
3. List changes made on your local
'''
git status
'''
4. Add the changes you want to push 
'''
git add <file names>
git add *   //to add all files listed
'''
'git status' should now show all files staged for commit in green
5. Commit your files
'''
git commit -m "type a message outlining changes here"
'''
6. Push your changes
'''
git push
'''
