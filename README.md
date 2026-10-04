# Isolated Windows approval-notice validation

Prepared and published by Agrippa under the repository owner's explicit authorization.

Contains only this README, the repair patch, and a validation workflow. No business documents, credentials, session logs, workspace history, or compiled artifacts are included.

The workflow uses the exact public upstream source for Windows tray 2026.9.4, verifies the patch hash, and runs the required build plus Shared and Tray tests on a standard public-repository Windows runner. It does not deploy, publish build artifacts, use paid runners, alter account settings, or change the owner PC.

Passing CI does not prove native visual timing, keyboard focus, cancellation, or real approval behavior. Those remain separate acceptance gates.

Free public standard-runner basis: https://docs.github.com/en/billing/concepts/product-billing/github-actions
