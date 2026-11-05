# PR #277 compatibility smoke test

- Source: catppuccin/jetbrains PR #277, c875c11201f9a7328e1f2e9e963c484dbcd57377, unchanged.
- Plugin: Catppuccin Theme 3.6.2, compatibility 231 through 263.*.
- IDE: IntelliJ IDEA Ultimate 2026.3, IU-263.7307.200, Windows x64.
- Build: Whiskers 2.9.0; Gradle 9.6.1; Java 21.
- buildPlugin, check and verifyPluginStructure passed.
- Packaged resources: all 8 UI variants and all 8 editor schemes parsed; referenced resources exist.
- JetBrains Plugin Verifier 1.411: Compatible against IU-263.7307.200.
- Installed JAR SHA-256: DC7DA79F1F4DE5F2F5F7F5A825E206EE39FF62922F2A2CEEBD5715CE4D97F997; identical to the locally built JAR.
- The IDE startup log confirms Catppuccin Theme 3.6.2 loaded after restart.
- Islands Catppuccin Mocha and the Catppuccin Mocha editor scheme rendered successfully.
- Manual visual smoke testing reported no regressions so far; this is not exhaustive visual coverage of every flavor, product, or OS.

Screenshots show only the public PR checkout and its appearance settings.

The plugin built from this PR still embeds 3.6.1 release notes; add the 2026.3 compatibility change to the changelog before release.
