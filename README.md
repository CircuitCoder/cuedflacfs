# CuedFLACfs
------

A FUSE library for mounting CUE/FLAC files to expose tracks as individual FLAC files.

## Motivation
I would really like to run a music streaming webapp on my NAS server running BitTorrent. Since I need to keep the original files for seeding, the most natural way is to use a webapp that directly supports CUE/FLAC files. Unfortunately, I could not find one. The closest I could find is airsonic, which has a pending PR (https://github.com/airsonic/airsonic/pull/856) that seemed ready to be merged.

This is my second attempt.
