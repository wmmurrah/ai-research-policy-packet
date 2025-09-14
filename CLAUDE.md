# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Quarto book project that creates a comprehensive AI research policy packet. The project generates both HTML and PDF documentation providing institutional guidance for responsible AI use in research.

## Project Structure

- **_quarto.yml**: Main configuration file defining the book structure, output formats, and styling
- **index.qmd**: Overview and quick start guide with ten key rules for AI use
- **policy.qmd**: Departmental policy covering scope, definitions, roles, and compliance
- **sop.qmd**: Standard operating procedures aligned to research lifecycle stages
- **checklists.qmd**: One-page checklists and risk assessment matrices
- **templates.qmd**: Ready-to-use disclosure language, forms, and documentation templates
- **appendices.qmd**: External references and regulatory mappings
- **_site/**: Generated output directory (HTML and assets)

## Common Commands

### Build the book
```bash
quarto render
```

### Preview locally with live reload
```bash
quarto preview
```

### Render specific format
```bash
quarto render --to html
quarto render --to pdf
```

### Clean build artifacts
```bash
quarto clean
```

## Content Architecture

The book follows a structured approach to AI governance:

1. **Quick Start** (index.qmd): Ten fundamental rules and role definitions
2. **Policy Framework** (policy.qmd): Institutional policies and compliance requirements
3. **Operational Procedures** (sop.qmd): Step-by-step processes for different research stages
4. **Implementation Tools** (checklists.qmd, templates.qmd): Practical resources for researchers
5. **Reference Materials** (appendices.qmd): Regulatory context and external guidance

## Customization Points

The content includes placeholder text marked with `[INSTITUTION]` and `[DEPARTMENT]` that should be customized for specific institutional deployment. Key customization areas include:

- Institution and department names
- Specific compliance requirements
- Local governance structures
- Approved AI tools and enterprise solutions

## Output Formats

The project is configured to generate:
- **HTML**: Interactive web version with navigation and search
- **PDF**: Print-ready document suitable for distribution

Both formats maintain consistent numbering, cross-references, and styling defined in the Quarto configuration.