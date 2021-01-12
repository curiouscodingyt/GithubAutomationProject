# GithubAutomationProject

Tool to automate the process of creating a GitHub repository locally and remotely with a one-line command.

## Configuration
```bash
$ python create_repo.py --help
```

| Argument  | Description |
| --------  | ----------- | 
| name      | Name of the repository. Required |
| private   | Makes repository private. Optional |

## Requirements
* Python, Git, GitHub Account + GitHub access token 
* Update variables `REPO_PATH`, `GITHUB_USER` and `GITHUB_TOKEN`

## Usage

To create a new repo run
```bash
$ pip3 install -r requirements.txt
$ python create_repo.py --name REPOSITORY_NAME
```

## YouTube video
Check the [video](https://youtu.be/QiHvRDcWRXI) 
