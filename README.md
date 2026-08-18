# Network Administration and Management

## Tech Stack
- Quarto
- R (knitr engine)
- renv (environment management)

## Colors

- website background: #0B2545

## Contents
```bash
pmpsti/
├── chapter1/
│   ├── ubuntuserver_installation.qmd
│   ├── images/
│   └── data/
│
├── index.qmd
└── _quarto.yml
```

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/solaemanachmad/labwork_amj.git
cd labwork_amj
```

### 2. Restore R Environment

Open R inside the project folder and run:

.RData

```r
renv::restore()
```

This will install all required packages based on `renv.lock`.

---

## Render Project

To render the full project:

```bash
quarto render
```

To preview locally:

```bash
quarto preview
```

---

## Notes

- All package versions are locked using `renv`
- Do not modify `renv.lock` manually
- Use branch-based workflow for major changes