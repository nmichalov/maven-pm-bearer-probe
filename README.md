# maven-pm-bearer-probe

Ephemeral probe for Endor Labs PackageManager **Google Artifact Registry** wiring on GitHub App (agentless) scans.

- Tenant namespace path: `endor-solutions-tgowan.gh_personal`
- Private dependency: `com.example.gar:gar-canary:0.0.1` in GAR `gowan-sandbox` / `endor-probe-maven` (`us-central1`)
- No secrets in this repo; registry auth is tenant PackageManager (`auth_provider.gar`)

Do not treat scan success/failure here as product SLA — this validates scan-time credential emission to Maven.
