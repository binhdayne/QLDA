# QLDA Middleware — Excel to Odoo MVP

Repository for the QLDA Integration Middleware project planning and data-analysis artifacts.

## Scope
Plan and demonstrate an MVP that validates and maps product-catalog data from Excel before importing it into a test Odoo environment. The repository currently contains project-management and analysis artifacts; it does not contain a deployed middleware application or live business data.

## Files
- `project-management/QLDA_Middleware_Project_Control_Baseline.xlsx` — schedule, WBS, resource, cost, risk, test, and project-control workbook.
- `project-management/QLDA_Middleware_MS_Project_Interchange.xml` — schedule interchange file for MS Project-compatible import.
- `project-management/QLDA_Middleware_Project_Import_Generic.csv` — generic task import data for project-management tools.
- `project-management/project_data.json` — structured planning data used to prepare project artifacts.
- `analysis/README.md` — scope, assumptions, tools, and reproduction notes for the analysis artifacts.

## Reproducibility and limits
Dates, effort, capacity, and labor-equivalent costs are planning assumptions and require team/instructor validation. Workbook preview images in the report are workbook renders, not screenshots of MS Project desktop. No credentials, API keys, or live customer data are included.

## Version-control requirement
Let `D` be the instructor's final submission date. Push the first meaningful project commit no later than `D - 21 days`, then continue committing meaningful changes. Do not backdate commits or manufacture history. Capture the actual GitHub commit history and repository URL in the final submission PDF.

## Safety
Do not commit secrets, access tokens, credentials, personal data, or unapproved source datasets. Use synthetic or anonymized samples in committed examples.
