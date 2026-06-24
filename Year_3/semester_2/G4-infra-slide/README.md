# G4-infra-slide

English README for the G4 Infrastructure Slides

## Project overview

This folder contains the presentation slides and related materials for "G4 - Infrastructure" (G4-infra-slide). The slides were prepared as part of the Year 3, Semester 2 project work in the Computer Engineering program. The purpose of the slides is to summarize the group's infrastructure design, deployment plan, and key findings.

## Contents

- Slide files (common formats): PDF, PowerPoint (.pptx), and source files (Markdown, reveal.js, or other).
- Images and diagrams used in the slides (in an images/ or assets/ subfolder if present).
- Supporting notes or scripts used to generate the slides.

Note: The exact filenames and formats in this folder may vary. Check the directory listing to see what is provided.

## How to view the slides

- If a PDF is present: open it with any PDF reader (Adobe Reader, Chrome, Preview, etc.).
- If a .pptx file is present: open with PowerPoint, LibreOffice Impress, or Google Slides (upload first).
- If slides are authored in HTML/reveal.js:
  - You can open the index.html in a web browser.
  - To serve locally, use a simple static server. For example, with Node.js installed:
    - Install a server: `npm install -g http-server` (if not already installed)
    - From the folder containing index.html run: `http-server -c-1` and open the printed URL in your browser.
- If slides are in Markdown and require a generator (Pandoc, mdx-deck, Remark, etc.), check for a build script or a README in the folder with generator-specific instructions.

## Requirements

- A web browser for HTML/PDF slides.
- PowerPoint or compatible viewer for .pptx files.
- Node.js (optional) if local serving or build tools are needed.
- Pandoc or other generators only if source files require conversion.

## Typical workflows

- To present: open the PDF or .pptx and use presentation mode.
- To edit: open the source file in the appropriate editor (PowerPoint for .pptx, a text editor for Markdown or reveal.js).
- To rebuild HTML slides from source: follow any build script provided (check package.json or scripts in the folder).

## Contributing

If you want to improve the slides or add materials:

1. Fork the repository (or create a new branch).
2. Edit or add slide files and assets in the G4-infra-slide folder.
3. Commit and open a pull request describing your change.

Please keep file formats consistent and avoid committing large generated files if a source-to-slides pipeline exists (commit sources rather than generated HTML/PDF when possible).

## License

Unless a specific license is included in the repository, assume standard academic use and include a license file if you want to permit reuse (e.g., MIT, CC-BY).

## Contact

For questions about these slides, contact the project owner or contributors listed in the repository metadata.
