# Generating a new SSH key and adding it to the ssh-agent
## 1. Open Git Bash.
## 2. Write this command in git bash and replace **developer@gmail.com** with your actual email address
```bash
ssh-keygen -t ed25519 -C "developer@gmail.com"
```
## 3. Config username and email address in git bash , 
### Replace **Mr. Developer** with your name and **developer@gmail.com** with your actual email address
### Name does not mean your GitHub username, that can be your nickname, your official name, or anything. Which will display when you check your git commit log
```bash
git config --global user.name "Mr. Developer"
git config --global user.email "developer@gmail.com"
```

