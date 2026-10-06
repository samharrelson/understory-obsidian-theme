# Contributing to Understory

Thanks for your interest in Understory.

Understory is a warm, quiet Obsidian theme for long-form reading, research, field notes, and writing. Contributions are welcome when they help the theme remain readable, calm, and useful without turning the interface into the foreground.

## Design principles

Changes should preserve the core principles of the theme:

- the note should remain the foreground;
- interface chrome should recede;
- color should differentiate, not decorate;
- long-form reading should feel closer to a book than a dashboard;
- research vocabulary can be supported visually without turning the vault into a taxonomy carnival.

When in doubt, prefer restraint.

## Before opening an issue

Please check existing issues first.

For bugs, include:

- Obsidian version;
- operating system and version;
- whether the problem occurs in light mode, dark mode, or both;
- whether CSS snippets or plugins are enabled;
- steps to reproduce the problem;
- screenshots when they help.

If a plugin or CSS snippet appears to be involved, note that clearly.

## Feature and refinement requests

Feature requests are welcome, especially when they improve:

- long-form readability;
- hierarchy and navigation;
- accessibility;
- consistency between light and dark modes;
- research callouts;
- tables, tags, links, and graph styling;
- compatibility with current Obsidian releases.

Please describe the problem you are trying to solve before proposing a visual treatment.

## Pull requests

For non-trivial changes, opening an issue first is encouraged.

When submitting a pull request:

1. Keep the change focused.
2. Explain what changed and why.
3. Test in both light and dark modes.
4. Test with a clean vault when practical.
5. Include screenshots for visual changes.
6. Note the Obsidian version and operating system used for testing.
7. Avoid unrelated formatting or cleanup changes in the same pull request.

## CSS conventions

Understory is intentionally small and hand-readable.

Please:

- prefer existing CSS variables before adding new ones;
- avoid overly specific selectors when a simpler selector works;
- keep comments useful and brief;
- group related changes together;
- avoid plugin-specific styling unless there is a compelling reason and the fallback remains graceful.

## Accessibility

Do not reduce contrast, focus visibility, or legibility for the sake of visual subtlety.

If a change affects text color, background color, focus states, links, tags, callouts, or interactive controls, please mention that in the pull request.

## Licensing

By contributing code or other material to this repository, you agree that your contribution may be distributed under the repository's existing license terms.

## Questions

If you are unsure whether an idea fits Understory, opening a discussion-style issue is welcome.
