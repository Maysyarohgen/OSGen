import os

def push_to_github():
    os.system("git add .")
    os.system("git commit -m 'Update OSGen files'")
    os.system("git push origin main")

 git init
git remote add origin https://github.com/Maysyarohgen/OSGen.git
git add .
git commit -m "Initial commit of OSGen"
git branch -M main
git push -u origin main   
