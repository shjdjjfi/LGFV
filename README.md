# LGFV Exit Stress Test — GitHub Pages package

This folder is a complete static webpage for the manuscript:

> **From Implicit Guarantees to Fiscal Reallocation: A City-Level Stress Test of Full LGFV Exit in China**

It can be published directly with **GitHub Pages**. No server, database, or GitHub Actions workflow is required.

## Files

```text
index.html                         # Landing page shown at the website root
paper.html                         # Full HTML manuscript supplied with the source package
assets/style.css                   # Page design and responsive layout
assets/adjustment_channels.png     # Browser-friendly image preview for Figure 1
assets/budget_capacity.png         # Browser-friendly image preview for Figure 2
figures/*.pdf                      # High-resolution figure PDFs
.nojekyll                          # Prevents Jekyll processing on GitHub Pages
```

## Publish in five minutes

1. Create a **new public repository** on GitHub. A suitable repository name is `lgfv-exit-stress-test`.
2. Upload the **contents** of this folder into the repository root. Do not upload the outer ZIP as a single file.
3. In the GitHub repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then click **Save**.
6. GitHub will publish the site at:

   ```text
   https://YOUR-GITHUB-USERNAME.github.io/lgfv-exit-stress-test/
   ```

The page may take a short time to become available after the first deployment.

## Recommended edits before publishing

Open `index.html` and update:

- The author line near `class="authors"`.
- The affiliation line near `class="affiliation"`.
- The footer copyright line.
- The BibTeX entry in the **Citation** section.
- Any links to a PDF, replication package, code repository, data documentation, or DOI once those are public.

## Anonymous-review warning

A GitHub Pages site is public. Do **not** publish it while the paper must remain anonymous for double-blind review. Even a pseudonymous website can expose authorship through the GitHub account, commit history, repository metadata, linked files, or a personal domain.

## Optional custom domain

You can attach a domain that you own later through **Settings → Pages → Custom domain**. Configure the domain in GitHub first, then add the DNS records required by your domain registrar. GitHub can provision HTTPS after the DNS configuration is valid.
