# release-bucket# artifact-cache

This repository is used for distributing prebuilt application artifacts and update metadata.

It contains:
- Release assets (binary files)
- Small JSON manifests used by update clients

There is no source code in this repository.

## Structure

- **Releases**
  - Immutable binary artifacts (versioned files)
- **latest.json**
  - Points to the most recent stable artifact
  - Includes checksum and size metadata for verification

## Notes

- Files published here are intended to be consumed programmatically.
- Artifacts are immutable once released.
- Manifests may change over time to point to newer versions.

## License

Distribution only. No license is granted for source code, as none is included.
