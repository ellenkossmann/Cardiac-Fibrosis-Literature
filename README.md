# Cardiac Fibrosis — A Literature Atlas

A responsive website in plain HTML, CSS, and JavaScript. No frameworks, external fonts, packages, or build step.

## Preview

Open `index.html` in any modern browser. The six topic views use hash URLs, so navigation, refresh, and browser history work on static hosts.

## Edit the content

The `topics` array in `index.html` defines the six topics, text, colours, and overview summary. The `artwork()` function renders the visual abstract placeholders. Replace its placeholder markup with images and descriptive alternative text when the abstracts are ready. The `papersByTopic` object contains the paper lists, keyed by topic ID. The cardiomyocytes topic contains 11 papers, the monocytes/macrophages topic contains 32 papers, and the fibroblasts topic contains 50 entries, and the endothelial-cells topic contains 26 entries, with summaries supplied by the project author. Fibroblast entry 43 is explicitly marked as an unverified citation. Entries without supplied source URLs remain unlinked. Add the other topics to the same object as their text becomes available. Topics without content continue to show explicitly labelled placeholders.

## Host on GitHub Pages

Copy `index.html` and `.nojekyll` to the root of your repository. In the repository settings, enable Pages for that branch and root folder. No build configuration or server is required. All URLs are relative or hash-based, so the site also works beneath a repository path.

The `.openai/hosting.json` file is only used for the local preview and is not needed on GitHub Pages.
