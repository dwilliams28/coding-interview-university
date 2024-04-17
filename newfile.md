git clone https://github.com/<YOUR_GITHUB_USERNAME>/coding-interview-university.git
cd coding-interview-university
git remote add upstream https://github.com/jwasham/coding-interview-university.git
git remote set-url --push upstream DISABLE  # so that you don't push your personal progress back to the original repo

git commit -am "Marked personal progress"
git pull upstream main  # keep your fork up-to-date with changes from the original repo

git push # just pushes to your fork
