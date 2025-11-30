# Triple Gyrus Core

Triple Gyrus Core is a standardized system for creating structured data that can be used with any written language. Its structure is optimized for analog-to-digital transformation with optical character recognition (OCR), accessibility, and universality.

**Version**: 1 (Initial Release)

**Date**: 2025-11-30

**DOI**: https://doi.org/10.5281/zenodo.17772031

## What Can You Do With Triple Gyrus Core?

1. Write it out by hand
2. Create Triple Gyrus Core overlays for existing documents to indicate where structured data exists
3. Take digital pictures of paper documents, mark them up with Triple Gyrus Core overlays, then extract data with OCR
4. Mark up complex digital documents (spreadsheets, PDFs, images) to ensure reliable extraction of structured content
5. Extract and organize data in a consistent, accessible format

## Design Philosophy

Triple Gyrus Core uses the **accessible path approach**: designing for all users and all real-world conditions from the start, and assuming that code will break unless tests prove otherwise. This is different from the "happy path" approach of designing for ideal conditions and adding accessibility later.

## Features

- **Universal**: Works with any written language
- **Accessible**: Designed with screen readers, speech-to-text, and tactile reading systems in mind
- **OCR-Optimized**: Syntax built to make OCR easier and more consistent
- **Simple**: Uses only 2 special symbols (caret `^` and plus sign `+`)
- **Structured**: Organizes data in triples for consistent, parseable extraction

## What's Included

- **Triple Gyrus Core.txt**: Complete specification and manual
- **editor.html**: Self-contained browser-based editor for examining and editing Triple Gyrus Core content
  - Works in any modern browser
  - No installation required
  - Enforces proper formatting automatically
  - Supports both LTR and RTL text
  - Respects user preferences (dark mode, reduced motion)
  - Fully accessible (WCAG AAA compliant)

## Quick Start

1. Read the specification in `Triple Gyrus Core.txt`
2. Open `editor.html` in any modern web browser to start creating or editing Triple Gyrus Core content
3. Create overlays for your documents following Section 4 of the specification
4. Extract data using OCR and refine in the editor

## Future Development

This initial release focuses on OCR data extraction. Planned expansions include:
- Semantic data format capabilities
- Turing-complete programming capability
- Additional markers and indicators for specialized use cases

## Licensing

All code and documentation in this project is licensed under the **GNU Affero General Public License v3.0 (AGPL-3.0)**.

This means:
- You can use, modify, and distribute this software freely
- Commercial use is allowed
- You must share your modifications under the same license
- If you run a modified version as a network service, you must make the source available to users

See the `LICENSE` file for full terms.

## Contributing

Contributions are welcome! Since this project uses AGPL-3.0, any contributions will also be licensed under AGPL-3.0. By submitting a contribution, you agree to license your work under these terms.

## Author

© 2025 Jessica Reuter Castrogiovanni  
https://jsrc.expert
