# CCNA Lab Reports (SRWE + ENSA)

Simple repo to store **PDF lab reports** (and optional LaTeX source) for the CCNA curriculum.

## Structure

- `SRWE/labs/<LAB_FOLDER>/`
  - `report.pdf` *(your final report for submission / portfolio)*
  - `report.tex` *(optional LaTeX source)*
  - `images/` *(optional screenshots referenced by LaTeX)*

- `ENSA/labs/<LAB_FOLDER>/` *(same idea as SRWE)*

- `templates/`
  - Reusable report template(s)

## Naming conventions (recommended)

- Lab folder: `1.3.6_Configure_SSH` (use the NetAcad lab ID + short title)
- PDF name inside each folder: `report.pdf` (keeps links stable)
- If you prefer dated PDFs, also drop a copy like: `2026-02-13_1.3.6_Configure_SSH.pdf`

## How to use

1. Create a new lab folder under `SRWE/labs/` or `ENSA/labs/`
2. Drop your finished `report.pdf` inside
3. (Optional) Keep your LaTeX and screenshots for reproducibility

## Quick example

```
SRWE/labs/1.3.6_Configure_SSH/
  report.pdf
  report.tex
  images/
    baseline_telnet_proof.png
    baseline_insecure.png
    hardening_steps.png
    ssh_validation.png
    ssh_config_verification.png
```
