# HAIR STUDIO 0.1.0-alpha — first Photoshop test

The first UI-only UXP prototype is available as a ZIP attachment in the ChatGPT development conversation. This branch records the initial test plan; the full source package has not yet been committed to GitHub.

## Testing

1. Extract the ZIP, open Adobe UXP Developer Tool, and select the extracted `manifest.json` using Add Plugin.
2. Load the plugin into Photoshop 24.0 or later.
3. Test the five accordion sections, drag-to-reorder, hamburger commands, Preferences and lock layout.
4. Test the version-aware welcome screen and footer `?` tooltip toggle.
5. Test persistence by closing and reopening the panel.
6. Report the first UXP Developer Tool error or screenshot.

## Explicit limitations

This build is an unverified UI shell. It does not draw hair, modify documents, sample colors, generate previews or connect to native Photoshop paths. The visual preset browser is not implemented.
