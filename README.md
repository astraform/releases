# Astraform releases

Official deployment downloads for Astraform, a platform for testing partner
agents through autonomous customer simulations.

This public repository hosts approved release downloads and installation
information. It does not contain the Astraform platform source code.

## Download and install

Choose a version from [Releases](https://github.com/astraform/releases/releases)
and download both its `astraform-platform-<version>.tar.gz` archive and matching
`.sha256` checksum. Verify the checksum before extracting the archive, then
follow the included `README.md` and `RELEASE-NOTES.md`.

The deployment bundle contains Docker Compose files, configuration templates
and operating instructions. Docker downloads the platform images pinned by the
bundle; you do not need the private platform repository or a platform source
build. Your agents, tools and business data stay in your environment.

Use the model profile, compatible SDK versions and installation limits stated
in the selected release. The platform bundle does not include a complete sample
partner service; starter availability is documented separately.

## Documentation and support

- [Astraform website](https://astraform.ai/)
- [Developer guides](https://astraform.ai/developers)
- [Partner Preview](https://astraform.ai/partner-preview/)

When requesting help, include the release version, image identities, run ID and
a redacted error. Do not post API keys, customer records or private diagnostic
logs in public issues.
