# Publication Audit

## Scope

This audit covers the three Power BI report files selected for the public portfolio repository.

## Results

- All three files are valid ZIP-based PBIX packages.
- All three packages contain embedded `DataModel` content.
- Every file is below GitHub's 100 MB per-file limit.
- No obvious passwords, access tokens, secrets, or private server names were found during the static scan.
- Power BI/Fabric report and dataset GUIDs remain as normal application metadata and do not grant service access.
- The original binary contents were not edited; publication copies were renamed only.
- SHA-256 fingerprints are recorded in `SHA256SUMS.txt`.

## Limitations

- Power BI Desktop is not available in the packaging environment, so report rendering and live interaction were not re-executed during this audit.
- GitHub cannot render PBIX dashboards. Portfolio screenshots should be exported from Power BI Desktop and added before or after initial publication.
- Any later report replacement requires a new privacy scan and updated SHA-256 fingerprints.

## Publication decision

The repository is structurally ready for GitHub publication. Screenshots are recommended but are not required to preserve or download the PBIX project files.

