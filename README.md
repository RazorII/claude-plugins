# Claude Code plugins

Plugins I've built for Claude Code and use myself. Add the marketplace once, then install only the plugins you want:

```
claude plugin marketplace add RazorII/claude-plugins
claude plugin install docpdf@razorii
claude plugin install gdocout@razorii
claude plugin install pdfintake@razorii
claude plugin install audiointake@razorii
```

| Plugin | What it does |
|---|---|
| [docpdf](https://github.com/RazorII/docpdf) | Converts Word documents (.docx, .doc, .rtf, .odt) to PDF headlessly, then checks the PDF's page count and fonts against the document. Works on macOS, Windows and Linux. |
| [gdocout](https://github.com/RazorII/gdocout) | Turns Google Docs, Sheets and Slides into Word, Excel and PowerPoint files, one link or a whole Google Drive saved offline, and copies everything else, with a report of every file. Files shared by link need no sign-in; the rest come through your own signed-in browser. Works on macOS, Windows and Linux. |
| [pdfintake](https://github.com/RazorII/pdfintake) | Turns scans, phone photos and PDFs into small, searchable PDFs on your own computer: images go in without losing anything, pages that are only pictures of text get an invisible OCR text layer, and a PDF whose text copies out as garbage gets its font map repaired. English is built in, and nine more languages download the first time a document needs one. Works on macOS, Windows and Linux. |
| [audiointake](https://github.com/RazorII/audiointake) | Transcribes recordings on your Mac and turns them into meeting notes: every word goes under the right speaker, the voices you enrolled are named, and a summary, decisions and action items sit above the transcript. Transcription never goes online. Core reads English and 24 more European languages, and optional packs add Hungarian and Thai. Works on Macs with Apple silicon. |

Each plugin lives in its own repository, with its own README, license and issues.
