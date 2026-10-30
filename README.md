# Agglomerative Hierarchical Clustering Lab

An educational customer-segmentation project built with Google Colab, Python, and a static interactive website published through GitHub Pages.

## Project components
- `index.html` — interactive browser dashboard with cluster-count slider, linkage selector, customer scatter plot, cluster-size chart, profile chart, summary table, silhouette score, and a small step-by-step hierarchical-clustering demonstration.
- `notebook/` — place your completed Google Colab notebook (`.ipynb`) here.
- `data/` — optional folder for a dataset copy if your instructor permits redistribution. The website currently loads the public Mall Customers CSV from its source repository.

## Features
- Mall Customers dataset: Annual Income and Spending Score.
- Agglomerative clustering with Ward, Complete, Average, and Single linkage options.
- Compare between 2 and 10 clusters.
- Interactive charts and cluster summary.
- Eight-point educational merge demonstration with Reset, Prev, Next, and Play/Pause controls.

## Publish with GitHub Pages
1. Upload these project files to a GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then click **Save**.
5. Wait for the deployment to finish. The live project URL will be shown on the Pages settings screen.

GitHub Pages publishes static HTML, CSS, and JavaScript. The Python notebook should be opened and run in Google Colab.

## Open the notebook in Google Colab
After uploading your notebook to GitHub, use this link format (replace placeholders):

`https://colab.research.google.com/github/YOUR-USERNAME/YOUR-REPOSITORY/blob/main/notebook/YOUR-NOTEBOOK.ipynb`

## Notes
- This is an educational browser implementation; exact numerical results can differ slightly from Python/scikit-learn due to implementation details.
- If the browser cannot load the CSV, check internet access and verify that the CSV source URL remains available.
- Before publishing, make sure you have permission to share all data and remove personal or sensitive information.
