# Privacy Policy Generator

This repository contains a small web application that generates a Privacy and Data Protection Policy based on a template. The template is stored in `template.txt` and uses placeholders enclosed in square brackets (e.g. `[COMPANY]`, `[CUSTOMER NAME]` and `[NAME SYSTEM]`). When running the app, you provide values for these placeholders via a form. The application replaces the placeholders with your values and outputs the completed policy, which you can then download as a plain text file.

## Running locally

No build step or installation is required. Simply open `index.html` in a web browser:

```bash
# from the repository root
open privacypolicy/index.html
```

Fill out the form and click **Generate**. The completed policy will appear on the page along with a download link.

## Placeholders

The template contains a number of placeholders which you can replace:

| Placeholder      | Description                               |
|------------------|-------------------------------------------|
| `COMPANY`        | Your company name                         |
| `CUSTOMER NAME`  | Name of the customer or legal entity      |
| `NAME SYSTEM`    | Name of the internal system or platform   |
| `_____`          | CEO name or signatory                     |
| `_______`        | Additional field for a miscellaneous value |

If a placeholder is left blank in the form, it will remain unchanged in the generated policy.

## Modifying the template

The privacy policy text is stored in `template.txt`. You can edit this file to tailor the policy to your needs. Make sure to keep the placeholder tokens (such as `[COMPANY]`) intact so the generator can replace them correctly.