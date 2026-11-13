# Install Headway 1 media

The website expects the media folders below the repository root.

1. Extract `Headway-1-Media-Pack.zip` into the repository root. It creates:
   - `media/videos/unit-01.mp4` … `unit-12.mp4`
   - `media/openers/unit-01-opener.mp4` … `unit-12-opener.mp4`
2. Extract `Headway-1-Audio-Pack.zip` into the same repository root. It creates:
   - `media/audio/index.json`
   - `media/audio/student-book/cd1`, `cd2`, `cd3`
   - `media/audio/workbook/unit-01` … `unit-12`
3. Open GitHub Desktop, select the `Headway-1` repository, review the new `media/` files, enter a commit message, choose **Commit to main**, then **Push origin**.

Do not extract the ZIPs inside another nested `Headway-1` folder. The resulting paths must start exactly with `media/`.

The players use local HTML5 video and audio sources. They do not use YouTube links. GitHub Pages cannot serve media files that are only in a ZIP or on your computer; the extracted files must be committed and pushed to GitHub.
