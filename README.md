git init
git flow init
git flow feature start my_feature
echo "Feature implementation" > feature.txt
git add feature.txt
git commit -m "Implemented feature"
git flow feature finish my_feature
git flow release start 1.0.0
git flow release finish 1.0.0
git push origin master
git push origin develop
git flow hotfix start hotfix1
echo "Urgent fix" > urgent.txt
git add urgent.txt
git commit -m "Added urgent fix"
git flow hotfix finish hotfix1
git push origin master
git push origin develop
