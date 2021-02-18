# Legal

CALA's Terms of Service, Privacy Policy, and other legal agreements.

## Modifying Documents

Our legal counsel often sends changes as DOCX files. These can be converted to
Markdown using a tool like [Pandoc](https://pandoc.org/).

```
$ pandoc input.docx -o designer-agreement.md --wrap none -t gfm-raw_html
```

Even with these options in place, it's usually necessary to do some manual
formatting cleanup; use GitHub to preview changes and generally try to match the
header/emphasis styling used in other files in this repo. Take care that
numbering, bullets, and indentation in particular match that of the original
document.

## Deployment

Markdown files in this repo are served by GitHub Pages at https://legal.ca.la.
PDF copies are built during CI and available and pushed to this same repo in the
`pdf/` directory.

## License

Unless otherwise indicated, these Terms of Use and all Content provided by CALA
are copyright © 2021 This Is Cala, Inc. All rights reserved. CALA and the CALA
logo are trademarks of This Is Cala, Inc.
