# spa-reports

Report pages from Saint Paul Agency. Each page is encrypted and opens only with its password.

Since Nov 24, 2026 the four internal client dashboards (`borton-volvo/`, `carlson-toyota/`, `dahl-honda-stevens-point/` and `car-donation-foundation/`) open with the SPA Dashboards password, the same lock as the SPA Dashboards hub at saintpaulagency.github.io. They are snapshots rebuilt from their Claude dashboards; each says the date its data runs through. `cdf-cpd-levers/` (WFW + Children's Wish: what's driving cost per donation) uses the same lock. `cdf-microsoft/` keeps its own password because it is made to share with Microsoft Advertising.

Each client's page lives in a folder named after the client (for example `borton-volvo/`, and `car-donation-foundation/` for Car Donation Foundation's internal dashboard, with its Microsoft page in `cdf-microsoft/`). The older folders (`dashboard/`, `microsoft/`, `dashboard-2/`, `dashboard-3/`, `dashboard-4/`, and since Oct 20, 2026 `cdf-google/`) only forward to the new ones, so links sent before keep working.

`cdf-cpd-levers/` (since Nov 24, 2026) is a one-off page for Car Donation Foundation. It isn't part of the daily rebuild.

`brand/spa-logo.png` is the Saint Paul Agency logo, used in the agency's internal docs.
