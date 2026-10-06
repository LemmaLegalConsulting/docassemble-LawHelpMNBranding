# docassemble.LawHelpMNBranding

LawHelpMN logo, Bootstrap theme, and favicon assets by Amanda Sauber.

## Use in AssemblyLine interviews

Install this package from https://github.com/LemmaLegalConsulting/docassemble-LawHelpMNBranding on your Docassemble server, then include the theme after AssemblyLine:

```yaml
---
include:
- docassemble.AssemblyLine:assembly_line.yml
- docassemble.LawHelpMNBranding:theme.yml
```

The include sets the Bootstrap theme, `al_logo`, and the LawHelpMN organization title and homepage. Remove interview-level overrides for those values to use the shared defaults. Assets are served from this package; consuming interviews do not need copies.

Favicon files are available for server configuration; the include does not change server-wide favicon settings.

## Remotes

`origin`: https://github.com/LemmaLegalConsulting/docassemble-LawHelpMNBranding

`upstream`: https://github.com/AmandaSauber/docassemble-LawHelpMNBranding

## Author

Amanda Sauber, alsauber@mnlegalservices.org
