## Steps to run notebooks(.ipynb):
- Open cmd and type `jupyter notebook` and enter.
- open the desired notebook from the browser.

### Run notebooks from any directory but using a particular project's virtual env.

What I mean by this is, suppose you have a root directory `D:/projects` and under it you have multiple ML projects each having their own `virtual env` under their respective folder.

```
D:
|
|___projects
    |
    |___project_1
    |   |___venv_1
    |   |___notebook_1 
    |
    |___project_2
        |___venv_2
```
Now, suppose you want to run `notebook_1` with `venv_2`,
in such case follow below step:
- goto project_2 dir
- open cmd
- activate `venv_2` with command `venv_2\Scripts\activate`
- run command `jupyter notebook --notebook-dir D:/projects`
- [x] This will open jupyter with `projects` as root directory.
- [x] Now you will have access to all projects directory, and you can open notebooks from any sub directories.