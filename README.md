# qmm2627

Website for the PhD course **Quantitative Methods Masterclass 2026-2027** @ Luiss Guido Carli (PhD in Politics).

Site: <https://francescovisconti.github.io/qmm2627>

## Structure

| File | Content |
|---|---|
| `index.qmd` | Course information, learning outcomes, requirements, reference books |
| `sessions.qmd` | The six sessions: topics, Stata labs, readings, applications, slides and materials |
| `assessment.qmd` | Participation, assignments, final paper, deadlines |
| `resources.qmd` | Stata setup, user-written packages, data used in the labs, open-access texts |
| `_quarto.yml` | Site configuration and navigation |
| `theme.scss`, `styles.css` | Styling |

## Workflow

Edit the `.qmd` files in RStudio, preview with **Build → Render Website** (or `quarto preview` in the terminal), then commit and push to `main` from the local clone (`~/Developer/qmm2627`, outside OneDrive) and publish with `quarto publish gh-pages`, which renders the site and pushes it to the `gh-pages` branch.
