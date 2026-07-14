<!-- DOI-BADGE-PLACEHOLDER: replace after first Zenodo release with the badge markdown Zenodo provides -->

# Reproducible R and Python data-science conventions for agentic coding

A reproducible R/Python data-science conventions ruleset for agentic coding in environmental, ecological, and geospatial work, written to be dropped into a Cursor project as an always-on rules file that steers agentic tools toward code that reads top-to-bottom and reruns cleanly.

## How to use

It's a Cursor rules file — place it under `.cursor/rules/` with the `.mdc` extension (e.g. `.cursor/rules/data-science-rules.mdc`). The `alwaysApply: true` front matter loads it on every request. The `.md` copy is for easy reading; rename it to `.mdc` when installing.

The conventions cover:

- Script structure
- File discipline
- Project layout
- Reproducibility and data integrity
- Geospatial/CRS handling
- Shared-server parallel/multiprocessing discipline
- Checkpointing
- Agent guardrails

## License

Released under [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) (public domain). Use it for any purpose, no attribution required. See the [LICENSE](LICENSE) file for the full text.

## How to cite

Attribution isn't required, but citation metadata is provided in [CITATION.cff](CITATION.cff). GitHub renders a "Cite this repository" button from it, and a Zenodo DOI will appear at the top of this README once the repository is archived.

Text citation:

> Broderick, C. (2026). Reproducible R and Python data-science conventions for agentic coding (Version v1.0.0) [Software]. https://github.com/NCEAS-AI/Carlo-Broderick
