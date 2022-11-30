# lxg-world
This python module has the function "world"
which will return a string "WORLD"

git init
touch __init__.py
touch requirements.txt
mate README.md
mate setup.py
mate pyproject.toml
git add README.md __init__.py setup.py requirements.txt pyproject.toml
git commit -m "first commit"
// I created a public repo in my personal account as a lxg_world.git
git remote add origin git@github.com:nwalshgit/lxg_world.git
git push -u origin master

pip install git+ssh://git@github.com/nwalshgit/lxg_world.git@master#egg=lxg_world
