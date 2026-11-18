# meal-matters
Meal Matters by Guarino Industries LLC: recipes priced by local groceries, time and budget.

Live at https://meals.guarinoindustries.com

The whole app is `index.html`. Everything you add stays in your own browser: your pantry, plans, imported recipes and dish photos. Recipe files and recipe photos are read on your device and never uploaded. The page loads nothing from other sites, fonts included, unless you point it at your own pricing server in its settings.

`vendor/` holds the parts served next to the page, each with its licence:

- `vendor/pdfjs`: pdf.js, for reading recipe PDFs (Apache License 2.0)
- `vendor/tesseract`: Tesseract.js and its English model, for reading recipe photos and scanned PDFs (Apache License 2.0). About 15 MB, loaded only the first time someone reads a photo.
- `vendor/fonts`: Atkinson Hyperlegible and Bricolage Grotesque (SIL Open Font License 1.1)

The app's own code is under the MIT License (see `LICENSE`).
