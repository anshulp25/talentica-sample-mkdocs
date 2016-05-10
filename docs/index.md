# Talentica Sample Project


### Pre-requisite

If python <= 2.7.9, then pip is required to be installed manually.

### Pip Installation

```bash
wget https://bootstrap.pypa.io/get-pip.py
python get-pip.py
```

### Virtualenv Installation

Virtualenv enables us to create virtual python environment, this gives advantage to install different python library versions for different projects which prevents the corruption of single python library repository.

```bash
pip install virtualenv
```

### Install mkdocs

```bash
cd /opt
sudo virtualenv mkdocs
sudo /opt/mkdocs/bin/pip install mkdocs
```

### Verifying mkdocs Installation

```bash
/opt/mkdocs/bin/mkdocs --version
```

### Creating new Project

```bash
/opt/mkdocs/bin/mkdocs new talentica-project
```

### Building the Website

Execute the below command in the Project Home directory of mkdocs.
```bash
/opt/mkdocs/bin/mkdocs build
```
