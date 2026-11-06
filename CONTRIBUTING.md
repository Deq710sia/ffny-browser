# Contributing to ffny-browser

Thank you for your interest in contributing to the project.

## Legal & Clean-Room Policy
This project strictly enforces clean-room development practices:
- **No Game Assets**: Never submit pull requests containing original game files, disc images (`.iso`, `.xiso`), extracted archives (`.viv`, `.mad`), proprietary textures, or audio clips.
- **No Leaked Code**: All contributions must be original code, clean-room reverse engineering, or derived from permissively licensed open-source projects (e.g. `xboxrecomp`, `xemu`).

## Development Workflow
1. Fork and clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the automated test suite before opening a pull request:
   ```bash
   npm test
   ```
4. Follow existing conventions across C/C++ (`runtime/`) and JavaScript modules (`web/`).
