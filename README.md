# ZCook

ZCook is a data-driven platform for discovering, organizing, and exploring cooking recipes.

The project focuses on building structured datasets for recipes, ingredients, and cooking metadata, enabling fast search, filtering, and analytics.

This repository explores how Shelby’s data infrastructure can be used to build scalable data pipelines and indexing systems for recipe-based applications.

---

## Project Goals

- Build structured recipe datasets
- Create scalable data pipelines
- Enable advanced search and filtering
- Experiment with Shelby data infrastructure

---

## Architecture

User → API → Data Pipeline → Shelby Storage → Query Engine → Application

### Components

**API Layer**
Handles recipe submissions and search endpoints.

**Data Pipeline**
Cleans and structures recipe datasets and ingredient data.

**Shelby Infrastructure**
Stores indexed datasets and enables fast queries.

---

## Data Types

### Recipes

- recipe_id
- title
- ingredients
- instructions
- cuisine
- cooking_time

### Ingredients

- ingredient_id
- name
- category
- nutrition_data

### Metadata

- tags
- ratings
- popularity_score

---

## Project Status

Early prototype exploring structured data workflows and Shelby infrastructure.

Project: **ZCook**
