# Contributing to FrontFamily

Thanks for your interest in contributing! Since the source code is in a private repository, contributions happen through issues on this repo.

## Ways to contribute

### Report a bug
If something isn't working correctly — wrong conversion output, CLI error, broken page — open a bug report with:
- What you did (paste the code you converted, or the CLI command you ran)
- What you expected
- What actually happened
- Your environment (browser, Node version, OS)

### Fix a component mapping
If you find a prop conversion that's wrong (e.g., MUI's `variant="contained"` should map to Chakra's `variant="solid"` but maps to something else), open a mapping correction issue with:
- Source framework and component
- Target framework and expected component
- The specific prop(s) that are wrong
- What the correct mapping should be

### Request a new framework or pattern
Want to see SolidJS, Svelte 5, or a specific pattern (e.g., Rich Text Editor, Calendar)? Open a feature request. Include:
- The framework/pattern name
- Why it would be useful
- Links to the framework's component docs

### Suggest a migration guide
If there's a migration path not covered (e.g., Mantine→MUI, Vuetify→Quasar), suggest it with:
- Source and target frameworks
- Why this migration is common
- Any specific gotchas you've encountered

## Code of conduct

Be respectful. We're building tools for developers — keep discussions technical and constructive.

## Response time

This is maintained by a solo developer. Issues are typically reviewed within a few days. High-impact bug reports and mapping corrections are prioritized.
