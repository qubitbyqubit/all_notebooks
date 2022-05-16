# Core QxQ Notebook Repository
[TOC]

## Quick Actions:

#### [Magic IQX Link for this repository](https://lab.quantum-computing.ibm.com/hub/user-redirect/git-pull?repo=https://github.com/qubitbyqubit/all_notebooks&urlpath=lab/tree/all_notebooks/README.ipynb&branch=main)

#### [Full Guidelines Doc (must have TCS Account)](https://docs.google.com/document/d/1U0oGSznUXcw3CG29AxF_z7rCdvuKGn70W9Z3zSjANWE/edit?usp=sharing)

## **Making *Magic* links for Material Distribution**

N.B. Gitpuller links are great for easily doing a git clone command straight into a jupyter lab environment without using the command line. Repositories must be public, and the since IQX only has a lab environment without a notebook tree "/hub/" must be used.

Git puller page: https://jupyterhub.github.io/nbgitpuller/link

**Specifics for IQX:**

IQX Slug: https://lab.quantum-computing.ibm.com

Example for this repo: (https://lab.quantum-computing.ibm.com/hub/user-redirect/git-pull?repo=https://github.com/qubitbyqubit/all_notebooks&urlpath=lab/tree/all_notebooks/README.ipynb&branch=main)

## Short Notebook guidelines

1. All notebooks are solution copies, using the form:

```python
# BLOCK 1
### Solution Start ###
def solution():
    return answer
### Solution End ###
```

2. Notebooks should include the reproduction clause at the end.



## Housekeeping notes

Large filesize warning, likely due to images - we will need to consider CDN for
including images/animations in the notebook files.

After the legacy conversion the tree will have to be scrubbed:
[docs](https://docs.github.com/en/enterprise-server@3.1/repositories/working-with-files/managing-large-files/about-large-files-on-github)


