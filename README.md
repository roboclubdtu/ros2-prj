# MKDocs Template for the DTU Roboclub 

This repository contains the template for a MKDocs-based Github hosted website.
The theme used here is [Material for MKDocs](https://squidfunk.github.io/mkdocs-material/).

This repository falls under the MIT Licence. Copyright (c) 2024 DTU-Roboclub

## Needed documentations

The documentations you might need to work with this template are:

- [MKDocs documentation](https://www.mkdocs.org/)
- [Material Theme documentation](https://squidfunk.github.io/mkdocs-material/)

## Installing Requirements

To build and work on your own device, you need to install some depencies. They are registered in the file `requirements.txt`. To install them, simply run:

```shell
pip install -r requirements.txt
```

## Using MKDocs on your device

You can run a mkdocs server on your computer to see on real-time your changes. For that, just run inside this directory:

```shell
mkdocs serve
```

And open the link shown in the console, which is a localhost address [127.0.0.1:8000](127.0.0.1:8000).

## Modifying and pushing the changes on Github

While on your pc you can use the command `mkdocs serve` to see the changes in real-time, to made them available only you have to push them. 

Thanks to an automated GitHub workflow (that you can found in the *.github/workflows* directory), the website is automatically built when a change is pushed on the `main` branch. It will export the made static website on the `gh-pages` branch.

When creating a new repository you may have to configure it so that it is a GitHub Page (Settings > Pages, then for the source select `deploy from branch`, and for the branch select `gh-pages` and `/(root)` as folder).

You may also need to allow the export of the static website by the workflow: Settings > Actions > General > Workflow permissions and select `Read and write permissions`.