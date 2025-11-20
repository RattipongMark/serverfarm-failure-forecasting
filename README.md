# 📁 Data Directory Setup

Before running or developing this project, please create the required data directories using the following structure:

```
data/
 ├── real_data/
 ├── clean_data/
 └── synthetic_data/
```

## 🛠 Create the folders (Linux / macOS / Git Bash)

Run this command in the project root:

```bash
mkdir -p data/real_data data/clean_data data/synthetic_data
```

## 🛠 Create the folders (Windows CMD)

Run this command in the project root:

```bash
mkdir data
mkdir data\real_data
mkdir data\clean_data
mkdir data\synthetic_data
```

## 🛠 Create the folders (Windows PowerShell)

Run this command in the project root:

```bash
New-Item -ItemType Directory -Path data/real_data, data/clean_data, data/synthetic_data
```

## 📥 Adding your data

Place your datasets into the corresponding directories:

* **Raw data** → `data/real_data/`

## 🚫 Why these folders are not pushed to GitHub

All directories inside `data/` are ignored by Git through the `.gitignore` file.
This prevents:

* Large files from bloating the repository
* Sensitive or private data from being uploaded
* Accidental commits of raw datasets


