
# TASK 4: Build a Version-Controlled DevOps Project with Git

## Objective
Manage a DevOps project using Git best practices.

## Tools
- Git
- GitHub

## Deliverables
- Project repository with proper commits and branching

## Steps

### 1. Initialize Repository and Push to GitHub
- Run `git init` to initialize your local repository.
- Create a new repository on GitHub.
- Add the remote: `git remote add origin <your-repo-url>`
- Push your initial commit: `git push -u origin main`

### 2. Create Branches
- Create `main`, `dev`, and `feature` branches:
	- `git checkout -b main`
	- `git checkout -b dev`
	- `git checkout -b feature/<feature-name>`

### 3. Use Pull Requests to Merge
- Develop features in `feature` branches.
- Open pull requests to merge changes into `dev` or `main`.
- Review and approve PRs before merging.

### 4. Add a Proper README.md
- Document project objectives, setup, usage, and contribution guidelines.
- Use markdown for clarity and structure.

### 5. Use .gitignore and Tags
- Add a `.gitignore` file to exclude unnecessary files.
- Use tags for releases: `git tag v1.0` and `git push --tags`

### 6. Document All Tasks Using Markdown
- Record all steps, commands, and decisions in markdown files.
- Keep documentation up to date for team collaboration.

## Example Branching Model
```
main
│
├── dev
│   └── feature/<feature-name>
```

## Best Practices
- Commit often with clear messages.
- Keep branches focused and up to date.
- Use pull requests for code review and collaboration.
- Tag releases for version tracking.

---

For more details, see the documentation in the `docs/` folder.
