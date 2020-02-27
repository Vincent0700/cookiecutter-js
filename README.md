# JavaScript 基础模板创建工具

## Feature

1. 基础配置文件生成
    - package.json
    - LICENSE
    - README.md

2. git 相关配置文件生成
    - .gitignore
    - .huskyrc.js
    - .lintstagedrc.js
    - .commitlintrc.js
    
3. eslint 相关配置文件生成
    - .eslintrc.js
    - .eslintignore
    - .prettierrc.js
    - .editorconfig
    - .vscode/settings.json

4. 生成完毕后执行 `yarn install`

## Structure

```text
rwxr-xr-x  3  vincent  staff    96 B    Wed Jan 22 16:59:37 2020  .vscode/
rw-r--r--  1  vincent  staff   397 B    Sun Feb 16 23:34:04 2020  .commitlintrc.js 
rw-r--r--  1  vincent  staff   146 B    Wed Jan 22 16:20:56 2020  .editorconfig 
rw-r--r--  1  vincent  staff    31 B    Wed Jan 22 16:20:56 2020  .eslintignore 
rw-r--r--  1  vincent  staff   322 B    Wed Jan 22 16:20:56 2020  .eslintrc.js 
rw-r--r--  1  vincent  staff    42 B    Wed Jan 22 16:59:37 2020  .gitignore 
rw-r--r--  1  vincent  staff   121 B    Sat Feb 15 13:16:32 2020  .huskyrc.js 
rw-r--r--  1  vincent  staff   158 B    Sat Feb 15 13:05:10 2020  .lintstagedrc.js 
rw-r--r--  1  vincent  staff     1 KiB  Sat Feb 15 12:33:17 2020  .prettierrc.js 
rw-r--r--  1  vincent  staff     1 KiB  Wed Jan 22 16:20:56 2020  LICENSE 
rw-r--r--  1  vincent  staff    34 B    Wed Jan 22 16:59:37 2020  README.md 
```

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
