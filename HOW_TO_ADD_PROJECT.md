# How to Add a New Project

To add a new Rust project to this repository in the future, follow these steps from your root folder (`C:\Users\yafit\Documents\Learn\Backend\Rust`):

**1. Create the new Rust project:**
```bash
cargo new my-new-project
```
*(This command creates a new folder named `my-new-project` with a `Cargo.toml` and a `src` directory).*

**2. Add the new project to git:**
```bash
git add my-new-project
```
*(Optional: You can also update the `README.md` to list the new project, then run `git add README.md` to include those changes).*

**3. Commit the changes:**
```bash
git commit -m "feat: add my-new-project"
```

**4. Push to GitHub:**
```bash
git push
```

That's it! Your new project is now tracked alongside your existing projects in this repository.