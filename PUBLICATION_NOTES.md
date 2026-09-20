# Maintenance and demo status

This Android coursework repository is being prepared for safer sharing.

- The legacy direct AI-service request and its embedded credential have been removed from ChatActivity.
- Chat currently displays an explicit disabled-demo message. A secure backend is required before restoring this feature; do not embed provider secrets in the Android app, BuildConfig, or distributable resources.
- Firebase client configuration is still present. Backend access rules and API restrictions require separate verification; configuration visibility is not authorization.
- Android build and device testing have not been repeated for this maintenance change.
- Previously published credentials must be revoked by their owners. Rewriting Git history does not invalidate a key or erase external copies.

History was sanitized while retaining commit authors and the sequence of work. Old clones must not be pushed back: they can reintroduce removed credentials. Keep this repository private until the outstanding credential and data checks are resolved.
