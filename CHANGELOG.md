# 📓 CHANGELOG – QuickTranslate+

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)  
This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html)

---

## [1.0.0] – 2025-06-23

### Added
- Initial working MVP with:
  - File upload: `.txt`, `.md`, `.docx`, `.pdf`
  - OpenAI GPT-4o / GPT-3.5 API integration
  - Translated text output as `.txt`
  - Simple Streamlit UI

---

## [1.1.0] – 2025-06-24

### Added
- Token counter using `tiktoken`
- Cost estimator based on OpenAI rates
- Source language auto-detection via `langdetect`
- Text chunking to support long documents
- Multi-chunk progress bar with feedback
- Translated summary output (3–4 sentence overview)
- File type-aware output: `.txt`, `.md`, `.docx`
- Multi-file upload support + `.zip` download

### Changed
- Refactored translation calls for modular chunking
- Switched to OpenAI Python SDK v1.0+ syntax

---

## [1.2.0] – 2025-06-25

### Added
- UI language toggle (English / Español)
- Privacy Mode toggle (disables Streamlit cache)
- Character limit enforcement (30,000 chars/file)
- Streamlit Cloud deployment
- Screenshot reference + live badge in README
- Full `README.md`, `build_log.md`, and `CHANGELOG.md`

---

## [Upcoming]

### Planned
- Export as formatted `.pdf`
- Inline glossary overrides
- Dark/light UI theming
- API version (RESTful endpoint)

