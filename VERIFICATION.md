# Verification plan — Audacity

Status: NOT RUN. There is no executable implementation to test.

## Module acceptance criteria

### 1. Export format worksheets

- [ ] Define a versioned input fixture specifically for export format worksheets.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

### 2. Loudness target notes

- [ ] Define a versioned input fixture specifically for loudness target notes.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

### 3. Listening review checklist

- [ ] Define a versioned input fixture specifically for listening review checklist.
- [ ] Document the expected output and units before implementation.
- [ ] Test valid, missing, malformed, and unsupported-version inputs.
- [ ] Repeat with the same fixture and compare results.
- [ ] Confirm that source files and unrelated settings remain unchanged.

## Release gate

- [ ] Implement the proposed modules and add automated tests.
- [ ] Record exact tested versions; leave untested versions marked unknown.
- [ ] Verify backups and restoration where state changes are supported.
- [ ] Review privacy, permissions, and product rules.
- [ ] Publish source and reproducible build instructions before claiming a working release.
- [ ] Do not present the retained external resource as a verified download.

## Scope

Observe and report first; any later change requires separate confirmation. Do not disable antivirus, updates, or other protections. No automatic data deletion or guaranteed performance gains. Do not collect passwords, tokens, or private file contents.
