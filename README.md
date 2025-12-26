# Aljwharah — Open Source (Code - OSS Based)


## The Repository

This repository (“**Aljwharah**”) contains the source code for a **Windows desktop code editor** built on top of **Code - OSS** (the open-source foundation behind the VS Code editor experience). Aljwharah focuses on a developer-first workflow with modern editor capabilities and product features designed for fast build–run–iterate cycles.

This repository is intended for:
- Core application code and platform integrations (Windows packaging, updates, configuration)
- Product features and UX (workspace experience, productivity tooling)
- Community collaboration (issues, pull requests, discussions)

## Aljwharah

Aljwharah combines the simplicity of a lightweight editor with what developers need for their daily edit-build-debug workflow. It provides rich code editing, navigation, debugging hooks, and an extensible architecture—while remaining intentionally focused on a fast and reliable Windows desktop experience.

### Highlights
- Familiar VS Code–style editor workflow (files, search, SCM, debugging, terminal)
- Product-level customizations (branding, defaults, curated experience)
- Extensible feature model (bundled functionality and optional extensions)
- Designed for modern development workflows (local projects, scripts, tooling integration)

> Note: Aljwharah is an independent project and is not affiliated with Microsoft. It is built from Code - OSS sources under the MIT license, with Aljwharah-specific customizations and distribution.

## Contributing

There are many ways to participate:
- Submit bugs and feature requests in **Issues**
- Help verify fixes by testing nightly/preview builds (when available)
- Review pull requests and propose improvements
- Improve documentation

If you want to contribute code, please see:
- `CONTRIBUTING.md` (how to build, run, debug, and test)
- `CODE_OF_CONDUCT.md` (community standards)

## Feedback

- Use **GitHub Issues** for bug reports and feature requests
- Use **GitHub Discussions** for questions and community support
- If security-related, please follow `SECURITY.md` (responsible disclosure)

## Related Projects

Aljwharah builds on the Code - OSS ecosystem and may integrate or bundle related components such as language tooling, debug adapters, and extensions. Where applicable, upstream projects will be referenced in documentation and attribution files.

## Bundled Features / Extensions

Aljwharah may ship with a curated set of built-in features and extensions to provide strong out-of-the-box language support and developer productivity. Details live in:
- `extensions/` (if present)
- `docs/` or release notes (for what’s included in each version)

## Development Container

This repository may include a Dev Containers / Codespaces setup for a consistent development environment. If available:
- Use the **Dev Containers: Open Folder in Container...** command
- See `.devcontainer/README.md` for requirements and performance recommendations

## Code of Conduct

This project follows a community Code of Conduct. See `CODE_OF_CONDUCT.md` for details.

## License

### Aljwharah
Copyright (c) Aljwharah contributors.
Licensed under the **MIT License** (see `LICENSE`).

### Upstream Attribution
Aljwharah includes or derives from **Code - OSS** sources. Upstream licenses and notices remain in effect and are preserved in the repository as required.
