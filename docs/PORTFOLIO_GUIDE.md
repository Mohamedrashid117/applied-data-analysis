# Maintain your Data Analyst GitHub portfolio

Your course work is valid evidence of practice. Use names describing the question or skill, explain that it was developed during training, and show clear findings. Keep your actual level and project results accurate.

## Suggested repository names

These are target names. They are not claims that the repositories have already been renamed.

| Existing name | Recommended name |
|---|---|
| `Assignments-Entru` | `python-data-analysis-foundations` |
| `Entri_Assignments` | `applied-data-analysis` |
| `car-price-prediction` | `car-price-analysis` |
| `hotel-booking-cancellation` | `hotel-booking-analysis` |

## Rename a repository yourself

1. Open your repository while signed in to GitHub.
2. Open **Settings**, then **General**.
3. Under **Repository name**, type the new name and click **Rename**.
4. Check the new repository URL and any links in your profile README.
5. In the corresponding local project folder, update the Git remote:

```bash
git remote set-url origin https://github.com/Mohamedrashid117/NEW-REPOSITORY-NAME.git
git remote -v
```

Replace `NEW-REPOSITORY-NAME` with the exact new name. GitHub generally redirects old repository links, but update links you maintain. Keep the same repository rather than recreating it, so its history remains available.

## Add descriptions and topics

On each repository's **Code** page, use the gear icon beside **About**. Add a one-sentence description and relevant topics, then save.

| Repository | Description | Topics |
|---|---|---|
| Car price | Python analysis of vehicle pricing patterns with EDA, regression comparison, and model interpretation. | `python`, `pandas`, `data-analysis`, `data-visualization`, `regression` |
| Hotel bookings | Historical hotel cancellation analysis with grouped validation, model evaluation, and a Flask demo. | `python`, `pandas`, `data-analysis`, `classification`, `flask` |
| Applied analysis | Python case studies in data cleaning, workforce analysis, statistics, and visualization. | `python`, `pandas`, `statistics`, `data-analysis`, `seaborn` |
| Foundations | Practical Python, NumPy, Pandas, and visualization exercises developed during Data Science training. | `python`, `numpy`, `pandas`, `jupyter-notebook` |

## Create your profile README

1. From GitHub's **+** menu, choose **New repository**.
2. Use the exact repository name **Mohamedrashid117**, matching your username.
3. Choose **Public** and enable **Add a README file**.
4. Create the repository, open `README.md`, and use the pencil icon to edit.
5. Copy the content of [`profile-README.md`](profile-README.md), update repository links if renamed, and commit the change.
6. Return to your profile and check that the introduction appears.

## Update your bio and pinned projects

On your profile, click **Edit profile**. Add your professional name, actual location, LinkedIn link, and this bio:

> Aspiring Data Analyst | BCA Graduate | Data Science Student at Entri | Python & Pandas | Seeking UAE opportunities | Available immediately

Use **Customize your pins** to select your strongest work. Suggested order: car price analysis, hotel booking analysis, applied data analysis, then foundations. Add a current professional photo when you have one available.

## Edit a README yourself

Open `README.md`, click the pencil, edit in Markdown, use **Preview**, and choose **Commit changes**. A useful project README includes the question, dataset, tools, workflow, key findings, charts, results, limitations, and instructions to run the project.

## Upload updates from VS Code

Open the terminal in the correct repository folder:

```bash
git status
git pull --ff-only
# Make and save your edits, then inspect them:
git diff
git add README.md
git commit -m "Explain analysis findings and setup"
git push origin main
```

Stage the actual files you changed. If Git reports local changes or a conflict during pull, inspect the message before proceeding; do not force-push to remove it.

## Before sharing a project

- Run from a fresh kernel using documented dependencies and relative file paths.
- Include a permitted dataset or give precise retrieval instructions.
- Explain charts in plain English and distinguish association from causation.
- Check metrics against the notebook's final results; do not call R² accuracy.
- Keep saved outputs consistent with code; rerun cells after changes.
- Keep current learning skills separate from demonstrated project skills.

You can choose a specialist domain later. These repositories currently show general Python analysis and modelling practice.
