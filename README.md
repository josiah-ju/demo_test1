echo "# demo_test1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:josiah-ju/demo_test1.git
git push -u origin main