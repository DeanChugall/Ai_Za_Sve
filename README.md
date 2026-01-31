# Ai Za Sve

domen: `aizasve.pro`

Cilj/Opis projekta....

# Useful Commands:

## Poetry

```bash
pip freeze > requirements.txt

# Export pip package to requirements.txt with poetry
poetry export --without-hashes --format=requirements.txt > requirements.txt

# Add lib to dev requirements using poetry
poetry add --group dev package_name

# Install libs from extras using poetry
poetry install --extras  extras_name

# Remove lib to dev requirements using poetry
poetry remove  package_name --group dev
```

## Git Commands

```bash
git status
git add .
git commit -m "message"
git push origin main

# Create the branch on your local machine and switch in this branch :
git checkout -b <NEW_BRANCH_NAME>
# Push the branch on github :
git push origin [name_of_your_new_branch]
# see all the branches
git branch -a

# push to branch
git push [name_of_your_branch]

```
