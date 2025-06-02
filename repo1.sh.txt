echo "Going to setup repo for CI Pipelines"
git init
git branch -m develop
mkdir ./src ./styles ./assets ./bin ./node-modules
touch ./.gitignore ./src/index.html ./styles/index.css
git config --local user.name "Sehar ch"
git config --local user.email "seharch123@gmail.com"
git config --local core.editor notepad
git remote add origin https://github.com/sehar0057/repo2.git
echo "||| Repo setup completed |||"
