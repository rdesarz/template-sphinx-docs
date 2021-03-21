# template-sphinx-docs
A template to quickly start a Sphinx documentation

# Install and build using venv

1. Create virtual environment

  python3 -m venv venv

2. Source environment and install theme

  source venv/bin/activate
  pip3 install sphinx sphinx_rtd_theme
  
3. Update `conf.py` with corresponding theme

4. Delete .git folder

  rm -rf .git
