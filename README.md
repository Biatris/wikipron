# wikipron

`wikipron` is a toolkit for scraping grapheme-to-phoneme (G2P) data from Wiktionary.

## Local Development

### Setting Up A Development Environment

1. Create a fork of this repo on GitHub.
2. Make sure you are in some sort of a virtual environment
   (venv, virtualenv, conda, etc).
3. Download and install the library within the virtual environment:

    ```bash
    git clone git@github.com:<your-github-username>/wikipron.git
    cd wikipron
    pip install --upgrade pip setuptools
    pip install -r requirements.txt
    pip install --no-deps -e .
    ```

### Running Tests

```bash
flake8 wikipron.py test_wikipron.py
pytest -vv test_wikipron.py
```
