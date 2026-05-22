# CICI Mainframe — Lab Refactor Batch 01

Baseline: `UI-Color-Test` branch.

## Purpose

Move the theme toward:

-   CICI Solutions as protagonist
-   `CICI Solutions — Notes from the Lab`
-   dark technical studio
-   AI/software lab
-   operational notes
-   project portfolio
-   subtle 70s/80s computing DNA
-   Courier Prime typography

## Files included

```text
home.hbs
partials/header.hbs
partials/footer.hbs
assets/css/tokens.css
assets/css/components.css
```

## Install steps

From the repo root:

```bash
git checkout UI-Color-Test
git pull origin UI-Color-Test
git checkout -b lab-homepage-refactor

cp /path/to/home.hbs ./home.hbs
cp /path/to/partials/header.hbs ./partials/header.hbs
cp /path/to/partials/footer.hbs ./partials/footer.hbs
cp /path/to/assets/css/tokens.css ./assets/css/tokens.css
cp /path/to/assets/css/components.css ./assets/css/components.css
```

## Font requirement

Add Courier Prime files to:

```text
assets/fonts/
```

Expected names:

```text
courier-prime-regular.woff2
courier-prime-bold.woff2
courier-prime-italic.woff2
courier-prime-bold-italic.woff2
```

Do not commit font files if the license/distribution terms are not clear.

## QA

```bash
npx gscan .
```

Then zip and upload the theme in Ghost admin.
