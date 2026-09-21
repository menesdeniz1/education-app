# Maintenance and demo status

This Android coursework repository is being prepared for safer sharing.

- The legacy direct AI-service request and its embedded credential have been removed from ChatActivity.
- Chat currently displays an explicit disabled-demo message. A secure backend is required before restoring this feature; do not embed provider secrets in the Android app, BuildConfig, or distributable resources.
- Original Firebase client configuration was removed from the current tree and reachable history. To build a connected version, supply app/google-services.json from your own test Firebase project, configure its access rules and use synthetic accounts only. It is gitignored. No original backend is configured by this source edition.
- Android build and device testing have not been repeated for this maintenance change.
- Previously published credentials must be revoked by their owners. Rewriting Git history does not invalidate a key or erase external copies.

History was sanitized while retaining commit authors and the sequence of work. Old clones must not be pushed back: they can reintroduce removed credentials. This is a source-only educational release requiring user-supplied Firebase configuration; Android build/device behavior remains unverified, not silently certified.
