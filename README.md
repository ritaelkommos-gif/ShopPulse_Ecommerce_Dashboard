[README.txt](https://github.com/user-attachments/files/34998083/README.txt)
# E-Commerce Customer Behavior Website

## Files
- index.html: website structure and Bootstrap layout
- style.css: website design
- script.js: data processing, charts, filter and table
- data.json: sample dataset[style.css](https://github.com/user-attachments/files/34998106/style.css)
[script.js](https://github.com/user-attachments/files/34998104/script.js)


## How to run
1. Open this folder in Visual Studio Code.* { box-sizing: border-box; }
body { background: #f5f6fb; color: #20243a; font-family: Arial, sans-serif; }
.site-header { background: linear-gradient(120deg, #34246b, #7155b8); color: white; }
.site-header h1 { font-weight: 750; letter-spacing: -.5px; }
.eyebrow { font-size: .75rem; letter-spacing: 2px; opacity: .8; }
.subtitle, .muted { color: #73788d; }
.site-header .subtitle { color: #e5e0f4; }
.section-title { font-weight: 700; }
.filter-box { min-width: 220px; }
.kpi-card, .chart-card, .source-note { background: white; border: 1px solid #e9e9f1; border-radius: 16px; padding: 22px; box-shadow: 0 5px 18px rgba(35, 30, 70, .04); }
.kpi-card p { color: #73788d; margin-bottom: 8px; }
.kpi-card h3 { display: inline-block; margin: 0; font-size: 2rem; font-weight: 750; color: #49358b; }
.kpi-card span { color: #73788d; margin-left: 5px; }
.chart-card h3, .source-note h3 { font-size: 1.1rem; font-weight: 700; }
.chart-wrap { height: 260px; position: relative; }
.finding { margin: 16px 0 0; padding: 11px 13px; background: #f2effb; border-left: 3px solid #7155b8; border-radius: 7px; color: #453777; font-size: .92rem; }
.record-count { color: #7155b8; font-weight: 700; font-size: .9rem; }
.table thead th { background: #f2effb; color: #433477; white-space: nowrap; font-size: .86rem; }
.table td { white-space: nowrap; font-size: .9rem; }
.source-note { border-style: dashed; }
footer { color: #777b8e; font-size: .9rem; }
@media (max-width: 576px) {
  .site-header h1 { font-size: 1.8rem; }
  .kpi-card, .chart-card, .source-note { padding: 17px; }
  .chart-wrap { height: 230px; }
}

2. Install the Live Server extension if it is not installed.
3. Right-click index.html and choose "Open with Live Server".
4. Keep all four files in the same folder.

The dataset is simulated for educational use and does not represent real customers.

## Publish on GitHub Pages
1. Create a new GitHub repository.
2. Upload all four files to the repository's main branch.
3. Open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select main and /(root), then Save.
6. Wait for GitHub Pages to publish and copy the website URL.
