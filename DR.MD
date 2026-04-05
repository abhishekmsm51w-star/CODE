# COMMANDS 


### for auth

```
gcloud auth application-default login
```


### FOR DEPLOYMENT 

```
uvx --from google-adk==1.14.0 \
adk deploy cloud_run \
  --project=$PROJECT_ID \
  --region=us-central1 \
  --service_name=drabhishek \
  --with_ui \
  . \
  -- \
  --labels=dev-tutorial=an-adk \
  --service-account=$SERVICE_ACCOUNT
```




FOR GITHUB 

```
git init
gh auth login
git config --global user.name "CHANGE USERNAME"
git config --global user.email "CHANGE EMAIL"

```

```
git init
git add .
git commit -m "initial commit"

git remote remove origin 2>/dev/null
git remote add origin {YOUR GITH LINK AS SHOWN IN VIDEO}

git branch -M main
git pull origin main --allow-unrelated-histories
git push -u origin main

git push -u origin main --force



```
