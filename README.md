# homestead-mksite
Script that clones github repository, adds entries to /etc/hosts and Homestead.yaml (including php version), and restarts vagrant



## Installation
Download `mksite`

`chmod a+x mksite`

`./mksite [repo_name]`

or copy to your favourite bin directory to execute from anywhere:

`mksite [repo]`


## Usage

### Settings to edit (within script):
```
homestead_path="$HOME/homestead"
project_path="$HOME/projects"
git_repo="git@github.com:PDERAS"
domain_prefix=""
domain_suffix=".test"
```
then:

`mksite [-h] [-c] [-w] [-v] [-d db_name] [-u url] repository_name`
