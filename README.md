# Claude Code plugins

Plugins I've built for Claude Code and use myself. Add the marketplace once, then install only the plugins you want:

```
claude plugin marketplace add RazorII/claude-plugins
claude plugin install docpdf@razorii
claude plugin install gdocout@razorii
```

| Plugin | What it does |
|---|---|
| [docpdf](https://github.com/RazorII/docpdf) | Converts Word documents (.docx, .doc, .rtf, .odt) to PDF headlessly, then checks the PDF's page count and fonts against the document. Works on macOS, Windows and Linux. |
| [gdocout](https://github.com/RazorII/gdocout) | Turns Google Docs, Sheets and Slides into Word, Excel and PowerPoint files, one link or a whole Google Drive saved offline, and copies everything else, with a report of every file. Files shared by link need no sign-in; the rest come through your own signed-in browser. Works on macOS, Windows and Linux. |

Each plugin lives in its own repository, with its own README, license and issues.
