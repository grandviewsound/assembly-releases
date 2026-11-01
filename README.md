# Assembly releases

Signed, notarized builds of Assembly for macOS, and the Sparkle feed
(`appcast.xml`) that installed copies check for updates.

Nothing here is edited by hand: `Scripts/release.sh` in the source repository
writes each archive and rebuilds the appcast, and every update is signed with a
key that is not in this repository.
