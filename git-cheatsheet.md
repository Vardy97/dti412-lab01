# Git Command Cheat Sheet

## 1. Check Git Version

```bash
git --version
```

Displays the installed Git version.

## 2. Configure Git Username

```bash
git config --global user.name "Your Name"
```

Sets the global Git username.

## 3. Configure Git Email

```bash
git config --global user.email "your-email@example.com"
```

Sets the global Git email address.

## 4. Check Git Configuration

```bash
git config --list
```

Displays Git configuration settings.

## 5. Clone a Repository

```bash
git clone repository-url
```

Downloads a remote repository to the local computer.

## 6. Check Repository Status

```bash
git status
```

Shows the current repository status.

## 7. Add Files

```bash
git add .
```

Stages all changes in the current directory.

## 8. Commit Changes

```bash
git commit -m "Your commit message"
```

Saves staged changes in the local repository.

## 9. Push Changes

```bash
git push
```

Uploads local commits to the remote repository.

## 10. Pull Changes

```bash
git pull
```

Downloads and integrates changes from the remote repository.

## 11. View Commit History

```bash
git log --oneline
```

Displays a short commit history.

## 12. Check Current Branch

```bash
git branch
```

Displays the current branch and available local branches.

## 13. Create a New Branch

```bash
git branch new-branch
```

Creates a new branch.

## 14. Switch Branch

```bash
git switch branch-name
```

Switches to another branch.

## 15. Create and Switch Branch

```bash
git switch -c new-branch
```

Creates a new branch and switches to it.