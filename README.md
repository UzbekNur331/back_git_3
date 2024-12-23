# Feature filialida
echo "Feature qo'shildi" >> conflict.txt
git add conflict.txt
git commit -m "Feature: conflict.txt fayliga o'zgarish"

# Bugfix filialida
git checkout bugfix
echo "Bugfix qo'shildi" >> conflict.txt
git add conflict.txt
git commit -m "Bugfix: conflict.txt fayliga o'zgarish"
"# back_git_3" 
