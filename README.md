# Backstage Software Catalog Demo

This directory contains sample data for the Backstage Software Catalog.

## Directory Structure

- `catalog-info.yaml`: Entry point for the catalog.
- `org/`: User and Group entities.
- `domains/`: Domain entities.
- `systems/`: System entities.
- `components/`: Component entities.
- `apis/`: API entities.
- `resources/`: Resource entities.

## How to Push to GitHub

Run the following commands in your terminal to initialize a git repository and push to GitHub:

```sh
cd backstage-software-catalog-demo
git init
git add .
git commit -m "Initial commit of sample catalog data"
git branch -M main
git remote add origin https://github.com/nontster/backstage-software-catalog-demo.git
git push -u origin main
```
