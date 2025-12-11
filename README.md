# iot_ketchup
This is a repo used for showing the capabilities of git

## Purpose

This repository contains sample files designed for live git demonstrations and training sessions. Each file serves a specific purpose in teaching different git concepts.

## Demo Files

### Files for Collaborative Editing
- **team_members.txt** - Perfect for demonstrating merge conflicts when multiple people edit the team roster
- **shopping_list.md** - Great for showing concurrent edits and conflict resolution
- **recipe.md** - A ketchup recipe that can be improved collaboratively

### Files for Feature Development
- **calculator.py** - Simple Python code for demonstrating feature branches and code reviews
- **config.json** - Configuration file for showing structured data changes
- **todo.txt** - Task list for tracking work and demonstrating incremental commits

### Files for Documentation
- **CONTRIBUTING.md** - Guidelines that can be updated as the "project" evolves

## Git Demo Scenarios

### Scenario 1: Basic Workflow
1. Clone the repository
2. Make changes to `shopping_list.md` (add your favorite snacks)
3. Stage and commit your changes
4. Push to the repository

### Scenario 2: Merge Conflicts
1. Two people edit `team_members.txt` simultaneously
2. First person commits and pushes
3. Second person tries to push and encounters a conflict
4. Resolve the conflict and merge

### Scenario 3: Feature Branches
1. Create a new branch: `git checkout -b feature/add-power-function`
2. Add a power function to `calculator.py`
3. Commit and push the branch
4. Create a pull request

### Scenario 4: Reviewing History
1. Use `git log` to view commit history
2. Use `git blame` on `recipe.md` to see who contributed what
3. Use `git diff` to compare versions

### Scenario 5: Reverting Changes
1. Make a mistake in `config.json`
2. Use `git restore config.json` to revert uncommitted changes
3. Or use `git revert <commit>` to undo a committed change

## Getting Started

```bash
# Clone the repository
git clone https://github.com/Lauro-Silva_rok/iot_ketchup.git

# Navigate to the directory
cd iot_ketchup

# Create your own branch
git checkout -b your-name/demo

# Make some changes
echo "- Your Name (Your Role)" >> team_members.txt

# Stage and commit
git add team_members.txt
git commit -m "Add myself to the team"

# Push your changes
git push origin your-name/demo
```

## Tips for Presenters

- Start with simple scenarios and build up to more complex ones
- Use visual tools like `gitk` or GitHub's network graph
- Encourage participants to create conflicts intentionally to learn resolution
- Show both command-line and GUI approaches

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on how to contribute to this demo repository.

---
*Happy Git Learning!*
