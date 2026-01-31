# Ai Za Sve

domen: `aizasve.pro`

Cilj/Opis projekta....

# Useful Commands:

### Pre-Commit:

```bash
pre-commit run --all-files
```

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
git checkout -b [NEW_BRANCH_NAME]
# Push the branch on github :
git push origin [NEW_BRANCH_NAME]
# see all the branches
git branch -a
# push to branch
git push [BRANCH_NAME]
# Delete a branch on your local filesystem :
git branch -d [NEW_BRANCH_NAME]
# To force the deletion of local branch on your filesystem :
git branch -D [NEW_BRANCH_NAME]
# Delete the branch on github:
git push origin :[NEW_BRANCH_NAME]`
```
