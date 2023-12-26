# regression

## Download Dataset

Go to the `kaggle.com/{account_name}/account` and download API token. Move kaggle.json to `~/.kaggle/` directory.

```bash
# Activate python virtual environment.
python3 -m venv venv
source venv/bin/activate

# Install dependent packages.
pip install -r requirements.txt

# Download dataset
python download.py
```

