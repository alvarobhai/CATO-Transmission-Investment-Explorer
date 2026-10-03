# GB Transmission Investment & CATO Opportunity Explorer

Interactive static dashboard for exploring the GB transmission investment pipeline and the subset of projects exhibiting characteristics relevant to potential competitive transmission procurement.

## GitHub Pages

1. Upload the contents of this folder to a GitHub repository.
2. Ensure `index.html` is in the repository root.
3. In GitHub, go to **Settings → Pages**.
4. Select **Deploy from a branch**, choose the relevant branch (normally `main`) and `/ (root)`.
5. Save. GitHub Pages will publish the dashboard from `index.html`.

## Dashboard structure

Default project universe:
- Beyond 2030 – Selected
- TWR

Optional additional universe:
- Beyond 2030 – Additional

Primary exploration characteristics:
- Project type
- MW / capacity
- Delivery window
- New / existing
- Project separability
- Investment driver

Additional filters:
- Project source
- Development stage / pipeline status

The dashboard is an analytical opportunity explorer. Its screening characteristics should not be interpreted as a determination of CATO eligibility or as a prediction of Ofgem decisions.

## Data

`data/GB_Transmission_Investment_Master_v0_1.xlsx` is the underlying master dataset used to develop the dashboard. The current dashboard prototype embeds the required display data directly in `index.html`, so the dashboard does not require the workbook to run.

## Notes

- The current master dataset contains MW/capacity fields rather than a consistently comparable project-capex (£m) field. The dashboard therefore uses MW/capacity as the project-size control.
- Some project characteristics in this prototype are analytical screening classifications and should be QA'd against source evidence before being treated as final.
- The dashboard deliberately does not use a map as its central visualisation.
