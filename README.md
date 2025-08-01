# Privacy Policy Generator

This repository contains a small web application that builds a Privacy and Data Protection Policy based on answers you provide in a form. The policy text is stored in `policy-template.txt` and uses placeholders enclosed in square brackets (for example `[CUSTOMER_NAME]`). When running the app, you provide values for these placeholders via a simple form. The application replaces the placeholders with your values and outputs the completed policy, which automatically downloads as a PDF using [jsPDF](https://github.com/parallax/jsPDF).

## Running locally

No build step or installation is required. Simply open `index.html` in a web browser:

```bash
# from the repository root
open privacypolicy/index.html
```

Fill out the form with company details, contacts, data practices and retention, and upload a company logo. Click **Generate** to display the completed policy on the page and download it as a PDF.

## Modifying the template

The privacy policy text is stored in `policy-template.txt`. You can edit this file to tailor the policy to your needs. Make sure to keep the placeholder tokens (such as `[CUSTOMER_NAME]`, `[NAME_SYSTEM]`, `[CEO_NAME]` and `[APPROVAL_DATE]`) intact so the generator can replace them correctly.
