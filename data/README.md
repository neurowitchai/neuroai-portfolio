# 📊 Data Directory

This directory contains datasets, processed files, and metadata used for the NeuroAI projects.

> 🔒 **Note**: Raw data files may be too large or restricted for upload. Placeholder files or download instructions are provided where appropriate.

---

## 📂 Directory Structure

```
data/
├── raw/ # Original datasets (unmodified)
├── processed/ # Cleaned, resized, or transformed datasets
├── external/ # Downloaded files or third-party data
├── interim/ # Intermediate processing steps
├── metadata/ # Labels, splits, info files
```

---

## 📥 Usage

- Place any downloaded datasets into `data/raw/`.
- Use preprocessing scripts to generate files in `processed/` or `interim/`.
- Store readme or dataset notes inside each subfolder when needed.

---

## 🧠 Example Datasets (planned or used)

| Dataset Name | Description | Source / Link |
|--------------|-------------|---------------|
| TBD          | TBD         | TBD           |

---

## ✅ Tips
- Add `.gitignore` in `raw/` if you’re not committing large files.
- Document preprocessing steps in a matching Jupyter notebook or script.

