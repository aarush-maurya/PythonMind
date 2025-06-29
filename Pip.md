## 🧾 Definition
**`pip`** stands for **“Pip Installs Packages”**. It is the **default package manager** for Python, used to install and manage software packages from the **Python Package Index (PyPI)** and other repositories.

## 🧩 Features
- Allows you to **install**, **upgrade**, and **uninstall** Python packages.
- Works with **PyPI**, the official Python package repository.
- Installed by default with Python versions ≥ 3.4.
- Can list all installed packages.
- Supports requirement files for batch installs.

## 🧪 Examples

### ▶️ Installing a Package
```bash
pip install requests
```

### ▶️ Installing a Specific Version
```bash
pip install numpy==1.24.3
```

### ▶️ Upgrading a Package
```bash
pip install --upgrade pandas
```

### ▶️ Uninstalling a Package
```bash
pip uninstall flask
```

### ▶️ Listing All Installed Packages
```bash
pip list
```

### ▶️ Saving Installed Packages to a File
```bash
pip freeze > requirements.txt
```

### ▶️ Installing from a requirements file
```bash
pip install -r requirements.txt
```

## 🧠 Tip
- If you have both Python 2 and Python 3 installed, use `pip3` for Python 3:
```bash
pip3 install package_name
```

- To check pip version:
```bash
pip --version
```