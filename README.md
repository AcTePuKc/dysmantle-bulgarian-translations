# DYSMANTLE Bulgarian Translations

Bulgarian localization mod for `DYSMANTLE`.

Current scope:
- Bulgarian text for the main game
- Bulgarian text for supported mod-added strings
- compatibility metadata for MoleEater's `Quality of Life` changelog and loading tips integration

## Repository layout

- `localizations/`
- `mod-info.xml`
- `mod-shared-translations-bulgarian-changelog.xml`
- `mod-shared-translations-bulgarian-tips.xml`
- `preview.jpg`

## Release flow

1. Test the mod locally in `DYSMANTLE Mods`
2. Update changelog/version if needed
3. Create a Git tag such as `v0.1.0`
4. Publish the release zip to GitHub
5. Publish the first version to Nexus manually
6. From `0.2.0` onward, Nexus publishing can be automated once the API key is configured

## Notes

- `Quality of life` and `Cheats` are intentionally left untranslated in the shared localization because the external mod UI does not render them correctly when localized.
- The repository is the source/master copy. The game folder copy is only for testing.

