git config --global user.name "Ogechukwuedeh"

git config --global user.email evelynoge08@gmail.com

cd C:/Users/User/Documents/projects

git init

git add .

git commit -m "my first commit - committing all files to the repository"

git remote add origin https://github.com/Ogechukwuedeh/my-first-project.git

git branch -M main

git push -u origin main

cd C:/Users/User/Documents

git clone https://github.com/Ogechukwuedeh/my-first-project.git

cd my-first-project

touch goals.txt

echo "My programming goals:
1. Become proficient in backend development.
2. Learn how to build secure and scalable APIs.
3. Contribute to open-source projects to improve my skills." > goals.txt

git add goals.txt

git commit -m "Added goals.txt with backend development goals"

git push origin main

git push -u origin main
