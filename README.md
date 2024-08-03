# My-first-github-repo
My first repository on GitHub
git init
git add README.md
git commit -m "Initial commit"
git remote add origin https://github.com/ApoorvaPandey-12/my-first-github-repo.git
git push -u origin master
curl -X POST \
  https://api.github.com/user/repos \
  -H 'Authorization: Bearer  github_pat_11BKJN20Y0WH14JQroKE3' \
  -H 'Content-Type: application/json' \
  -d '{
        "name": "my-first-github-repo",
        "description": "My first repository on GitHub",
        "private": false
      }'
