# Cookiecutter - Ansible Role

A cookiecutter project template for Ansible roles. By using [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/), consistent Ansible projects can be
achieved with common constructs.

## Requirements

- [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/installation.html)

## Usage

Execute the following and answer the relevant questions.

```bash
cookiecutter https://github.com/mrlesmithjr/cookiecutter-ansible-role
```

### Example

In this example we will create an Ansible role for NGINX.

```bash
cookiecutter https://github.com/mrlesmithjr/cookiecutter-ansible-role
...
role_name [Enter Ansible role name]: test-role
description [Enter description of Ansible role]: A test role
author_name [Your Name]: Larry Smith Jr.
github_username [Enter your GitHub username]: mrlesmithjr
github_repo_name [Enter your GitHub reponame]: ansible-role-foo
```

## Licensing

The current licensing model is MIT by default.
