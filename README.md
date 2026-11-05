# pl1 FFmpeg corresponding source

This repository publishes the corresponding source for the FFmpeg and FFprobe builds that Q-Jam B.V. ships with pl1,
as the GNU Lesser General Public License (LGPL) version 2.1 or later requires.

Each GitHub release is named `ffmpeg-<version>-<recipe hash>`, the same name as the build it belongs to, and holds:

- the upstream FFmpeg source tarball and its signature, exactly as published by the FFmpeg project;
- the source of every library the build links (for example libvpl);
- any patches applied, and the exact configure line used for each target;
- a `SHA256SUMS` file covering all of the above.

The builds are LGPL-only: configured with `--disable-gpl --disable-nonfree --disable-version3` and linked
dynamically, so the FFmpeg libraries can be replaced.

FFmpeg is a trademark of Fabrice Bellard, originator of the FFmpeg project. This repository is not affiliated with the
FFmpeg project.

Questions: privacy@q-jam.nl — Q-Jam B.V., <https://q-jam.nl>, KvK 24399562.
