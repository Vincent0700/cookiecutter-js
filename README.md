# JavaScript 基础模板创建工具

## Feature

1. 基础配置文件生成
    - .gitignore
    - package.json
    - LICENSE
    - README.md
    
2. eslint 相关配置文件生成
    - .eslintrc.js
    - .eslintignore
    - .prettierrc.js
    - .editorconfig
    - .vscode/settings.json

3. 生成完毕后执行 `yarn install`

## Usage

1. 安装 `cookiecutter`

```bash
$ pip install cookiecutter
```

2. 使用模板

```bash
$ cookiecutter gh:vincent0700/cookiecutter-js

project_name [project_name]: demo
author [vincent0700 (https://vincentstudio.info)]:
email [wang.yuanqiu007@gmail.com]:
description [say somthing]: a demo project
```
