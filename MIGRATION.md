# Migration note

This package is a **static replacement** for the existing HugoBlox-based repository.

The execution environment used to prepare this package could read the public repository on GitHub but could not complete a network-level `git clone`. For that reason, the package does not include the old `.git` history or every old Hugo source file.

Recommended workflow:

```bash
git clone https://github.com/IsabelChuizaca/IsabelChuizaca.github.io.git
cd IsabelChuizaca.github.io
git checkout -b backup-hugo
# commit/push backup branch if desired

git checkout main
# replace the Hugo project files with the contents of this package
```

If you want to preserve selected old assets (CV, portrait, PDFs), copy them into the new `assets/` directory and update the links in `index.html`.
