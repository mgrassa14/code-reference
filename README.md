# Quality of Life commands
_keep very long, single line comments or codes within the some screen (windows)_
```
Alt + Z
```

# File commands
_make folder_
```
mkdir (name)
```
_make file_
```
touch (name)
```
# Git commands

### Update git repo for code/project
_add comment_
```
git add -A
git commit -m "comment..."
```
_change branch from master to main_
```
git branch -M main
```
_push up saved changes from code to repo_
```
git push origin main
```
_pull saved changes from repo to code_
```
git pull origin main
```
# Django commands
_start running database_
```
sudo service postgresql start
```
_stop running database_
```
sudo service postgresql stop
```
_check status of database_
```
sudo service postgresql status
```
_connect to postgres service and open psql shell_
```
sudo -u postgres psql
```
```
\q or CTRL + D (exit)
```
_make virtual environment_
```
virtualenv (name)
```
_open virtual environment_
```
source (name)/bin/activate
```
_close virtual environment_
```
deactivate
```
_check django version_
```
django-admin --version
```
_check python3 version_
```
python3 -V
```
