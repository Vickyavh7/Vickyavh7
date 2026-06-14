# GitHub Profile README — Setup

This folder powers your GitHub profile at https://github.com/Vickyavh7 once pushed.

## One-time: Create the repo on GitHub

1. Go to https://github.com/new
2. Repository name: **Vickyavh7** (must match your username exactly)
3. Description: `DevOps Engineer | Kubernetes | Open Source @ Coral`
4. Public, **no** README / .gitignore / license (we have files locally)
5. Click **Create repository**

## Push (SSH key already configured)

```powershell
cd C:\Users\vicky\Vickyavh7
git add README.md SETUP.md
git commit -m "Add DevOps profile README inspired by Coral OSS contributors"
git branch -M main
git -c "core.sshCommand=ssh -i C:/Users/vicky/.ssh/yes -o StrictHostKeyChecking=no" push -u origin main
```

## After push — GitHub profile settings

1. **Bio** (https://github.com/settings/profile):
   ```
   AI Infrastructure & DevOps Engineer | Kubernetes | LLMOps | Open Source @ Coral
   ```

2. **Website**: https://www.linkedin.com/in/vicky-avhad-956982270/

3. **Pinned repositories** (6 max, pick 5):
   - `Vickyavh7/cloudhireops`
   - `Vickyavh7/coral`
   - `withcoral/coral` (if you contributed — pin upstream)
   - Your best K8s/observability showcase repo (create next)

4. **Profile photo** — use same as LinkedIn for consistency

## LinkedIn link verified

- https://www.linkedin.com/in/vicky-avhad-956982270/
- DevOps Engineer, Thane, Maharashtra
- AWS SAA + Developer Associate, Databricks GenAI
