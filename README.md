# Customer Behaviour Analysis — MDS Project Website

A responsive website presenting our Mathematical Data Science (MDS) project, **Analysis of Customer Purchasing Behaviour Using Data Mining and Machine Learning**.

The website brings together the project's objectives, dataset, analytical methodology, visualisations, key findings, and customer segmentation results in a single, accessible interface.

## About the Project

The project studies online retail transactions to identify patterns in product sales, geographic demand, revenue trends, and customer purchasing behaviour.

Using the UCI Online Retail dataset, the analysis covers data preprocessing, product-level sales comparisons, product correlation, monthly revenue analysis, and customer segmentation using RFM features and K-Means clustering.

## About the Website

The website is designed to present the project's technical work in a clear, structured, and visually engaging format.

### Sections

- **Overview:** Introduces the project and its objectives.
- **Dataset:** Highlights the dataset and key preprocessing statistics.
- **Methodology:** Summarises the major stages of the analysis.
- **Results and Visualisations:** Presents the six figures from the project report, including product performance, geographic patterns, monthly revenue, and customer segmentation.
- **Customer Segmentation:** Explains the four identified customer groups and compares their RFM characteristics.
- **Project Team:** Introduces the team members.

### Design and Features

- Responsive layout for desktop, tablet, and mobile screens.
- Clean typography using Manrope and DM Sans.
- Muted forest-green, sage, and warm off-white colour palette.
- Alternating result-card layouts for readability.
- Dedicated image areas for report figures, with separate panels where appropriate.
- Responsive navigation and scroll-reveal effects.
- Reduced-motion support for accessibility.
- Built using plain HTML, CSS, and JavaScript, without a frontend framework.

## Technology Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and project content |
| CSS3 | Layout, styling, responsiveness, and animations |
| JavaScript | Navigation and interactive behaviour |
| SVG / PNG / JPG / WebP | Figures, illustrations, and team images |

## Running Locally

1. Download or clone the repository.
2. Open `index.html` in your browser.

Alternatively, start a local server from the project directory:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Adding Project Figures

The website includes placeholders for the figures in the project report. Replace them with the corresponding exported plots and update their image paths in `index.html` if necessary.

The report contains six numbered figures:

1. Data preprocessing
2. Product-level sales analysis
3. Product sales correlation
4. Geographic sales patterns
5. Monthly revenue trends
6. Customer segmentation using the elbow method and PCA

Figures containing panels (a) and (b) may be displayed as separate cards to give each visualisation more room and improve readability.

For best results, export the plots at high resolution and ensure that axis labels, legends, and annotations remain legible.

## Adding Team Photos

Place team portraits in `assets/team/` and update the corresponding image paths in `index.html`.

Expected filenames:

- `prajwal.jpg`
- `gourav.jpg`
- `prayunj.jpg`

Team descriptions and individual contributions can also be edited directly in `index.html`.

## Project Findings

The website presents findings reported in the MDS project, including:

- 541,909 original transaction records and 524,878 records after cleaning.
- Customer segmentation based on 392,692 cleaned transactions with known customer IDs, representing 4,338 customers.
- A Pearson correlation of approximately 0.684 between the invoice-level sales of two selected products.
- November as the highest observed monthly revenue period, with December representing a partial month.
- Four K-Means customer segments, with the first two PCA components explaining approximately 93.86% of the variance in the standardised RFM data.

The website's content is based on the project report. Interpretations and suggested business actions are presented as analysis rather than as independently validated outcomes.

## Repository Structure

```text
.
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── figures/
│   └── team/
└── README.md
```

- `index.html` contains the website's content and structure.
- `styles.css` controls the visual design and responsive layout.
- `script.js` handles navigation and interactive effects.
- `assets/figures/` stores the project visualisations.
- `assets/team/` stores team portraits and related assets.

## Project Team

- Prajwal B
- Gourav Sherikar
- Prayunj V N

## Acknowledgement

The analysis uses the **UCI Online Retail dataset** to investigate customer purchasing behaviour through data mining and machine learning techniques.

---

*Mathematical Data Science (MDS) Project*
