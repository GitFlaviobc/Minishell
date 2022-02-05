# Minishell - A small Shell but a lot of team work

<h1 name ="content" align = "center">📋 Table of contents</h1>
<p align = "center">
  <a href = "#intro">Intro</a> -
  <a href = "#goal">Goal</a> -
  <a href = "#tec">Tecnology</a> -
  <a href = "#function">Functionality</a> -
  <a href = "#how">How to use</a> -
  <a href = "#test">Tests</a> -
  <a href = "#update">Update</a> -
  <a href = "#author">Author</a>
</p>

<a name="intro"/> <h2> Intro </h2> </a>
- This project was done in duo with [Rafael Lacerda](https://github.com/rafalacerda1530)
- This is a minishell, recreate some of the shell functionality.
- Learned a lot about how the shell works inside and some new commands.
- My first project in a team (duo).
- We decided to work together on the tasks. And I learned that 2 brains makes thinking process more efficient.
- I learned about pipes, tolkens, execve, builtin functions, and a lot about shell commands. 
- Fixed more my knowledge about signals, parsing, File Descriptors, manipulate files.
- After I finished the project I looked for ways of parsing (because it was a lot of work). I found things about parsing algorithms and compiler design. I will study more about this. 
<p></p>
<a href = "#content">📋</a>

<a name="goal"/> <h2> 🎯 Goal </h2> </a>
- The goal is to recreate some functionality of the shell.
- Read the line input and save the history
- Builtin commands: 
    - echo, with/out flag -n
    - cd
    - pwd (no options)
    - export (no options)
    - unset (no options)
    - env (no options)
    - exit (no options)
- Single quotes, inhibit all interpretation of a sequence of characters.
- Double quotes, inhibit all interpretation of a sequence of characters except for $.
- Redirects
    - <
    - >
    - <<
    - >> , No history update
- Pipes
- Environmment variables
- $?
- Signals ctrl+d , ctrl+\ , ctrl+c
- execve to execute other shell commands
<p></p>
<a href = "#content">📋</a>

<a name="tec"/> <h2> 🛠️ Tecnology </h2> </a>
- Language: C
- VS code
- WSL ubuntu
- Norminette 42 (code norm used by école 42)
<p></p>
<a href = "#content">📋</a>

<a name="function"/> <h2> 📚 Functionality </h2> </a>

⚠️🚧

<p></p>
<a href = "#content">📋</a>

<a name="how"/> <h2> 📖 How to use </h2> </a>

- Clone the repository
```bash
git clone https://github.com/GitFlaviobc/Minishell
```
- to create the minishell
```bash
make
```
or
```bash
make all
```
- to delete all obj (.o) files created
```bash
make clean
```
 - to delete all created files
```bash
make fclean
```
 - to delete all files and recreate the minishell
```bash
make re
```
- to run the minishell, feel free to test any commands.
```bash
./minishell
```
<p></p>
<a href = "#content">📋</a>

<a name="test"/> <h2> 👨‍💻 Tests </h2> </a>
- The makefile is compiling with fsanitize to check for leaks.
- No special teste for this minishell, you can type some of the shell commands.
<p></p>
<a href = "#content">📋</a>

<a name="update"/> <h2> 🆙 Updates </h2> </a>
- The code I sent to evaluation will be kept the same. Any update will be on the update folder.⚠️🚧
<p></p>
<a href = "#content">📋</a>

<a name="author"/> <h2> 😀 Author </h2> </a>
Name: Flávio Bonini Campos
<p></p>

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/flaviobc88/)
<p></p>
<a href = "#content">📋</a>
<p></p>
