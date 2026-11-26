# 🧠 Netrum Dev-Hunting Program

Welcome to the **Netrum AI Dev-Hunting Program** – a community-driven registry for TypeScript developers contributing to the Netrum ecosystem. Follow the steps below to register yourself as a developer and get your PR merged into the official registry.

---

## 📌 Requirements

- Node.js (v18 or above)
- GitHub account
- Basic knowledge of TypeScript

---

## 🚀 Steps to Contribute

### 1️⃣ Fork the Repository

👉 Go to [NetrumAI/Netrum-Dev-Hunting](https://github.com/NetrumLabs/netrum-dev-hunting)  
Click the **Fork** button to create your own copy.

---

### 2️⃣ Clone Your Fork

```bash
git clone https://github.com/<your-github-username>/Netrum-Dev-Hunting.git
```

   - Enter Folder 

   ```bash
   cd Netrum-Dev-Hunting
   ```

### 3️⃣ Install Dependencies

```bash
npm install
```

### 4️⃣ Add Your Developer Profile

👉 Create your folder in the `dev/` directory:

```bash
mkdir dev/<your-name>-dev
```

👉 Add a file named `application.md` inside your folder.

📄 Example:

```bash
dev/youname-dev/application.md
```

Paste this template inside `application.md`:

```bash

#  🧑‍💻 YoureName - Application

- **Nmae**: Your Name 
- **Discord**: Discord Username
- **GitHub**: https://github.com/username
- **Languages**: 
- **Experience**: 
- **AI Tools**: 
- **Why Join?**: 

```

5️⃣ Run in Development Mode

Check if your profile is loading correctly:

```bash
npm run dev
```

✅ Output will look like:

```bash

🚀 Application loaded
✅ Registered Developers:
1. Your Name

```

6️⃣ Build Project

This will compile the TypeScript files into `/dist`:

```bash
npm run build
```

Then run the production output:

```bash
npm run start
```

✅ Output should still show your developer name.


### 7️⃣ Commit and Push

```bash

git add .
git commit -m "Added my developer profile"
git push origin main

```

### 8️⃣ Create Pull Request (PR)

- Go to your GitHub forked repo

- Click “Compare & Pull Request”

- Submit the PR to main branch of [NetrumAI/Netrum-Dev-Hunting](https://github.com/NetrumLabs/netrum-dev-hunting)


🎉 That’s it! You’re now officially part of the Dev-Hunting program!



# 👨‍💻 Maintained by

Netrum Labs | 🌐 [https://netrumlabs.com/](https://netrumlabs.com/)  
Join our Discord for help 💬 [https://discord.gg/87hVVDuppf](https://discord.gg/87hVVDuppf)


## After your PR is merged

- Your profile appears in the `dev/` registry once the maintainers merge your PR.
- Keep your fork in sync before opening a new PR: use the "Sync fork" button on GitHub, or `git fetch upstream` then `git rebase upstream/main`.

## Troubleshooting

- **`npm install` fails** - make sure Node.js v18 or above is installed (`node -v`), then delete `node_modules` and `package-lock.json` and run `npm install` again.
- **Wrong folder name** - your profile must live in `dev/<your-name>-dev/application.md`; a different folder name will not be picked up by the registry.
- **PR not showing your profile** - check that `application.md` is inside your own `dev/<your-name>-dev/` folder and that the file is committed on your branch, not on `main`.
