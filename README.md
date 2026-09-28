# AIVC demo media

Video assets for the [UCLA AIVC Lab demo gallery](https://www.math.ucla.edu/aivc/demo/).

- `originals/`: source videos, full-resolution composites, and requested crops. Any processing is recorded in `manifest.json`.
- `videos/`: 720p, 30 fps H.264 versions for inline playback, with fast-start metadata.
- `posters/`: video frames displayed before playback.
- `manifest.json`: dimensions, duration, original SHA-256 checksums, and file sizes.

Assets are served by GitHub Pages at `https://cffjiang.github.io/aivc-demos/`.
The gallery's layout and ordering are maintained in the lab website repository.

## BladeMaster videos

Five source clips from `https://jango6324.github.io/assets/blademaster/videos/` are preserved in `originals/`; their source URLs and checksums are recorded in `manifest.json`.

`02-banana-sim-real-30fps.mp4` combines the banana simulation on the left with the real experiment on the right. Both sources have 839 frames at 30 fps and start together at their original speed. The composite is 1884 x 720, without cropping or text overlays.

The gallery uses this comparison once, alongside sequential slicing, deep cuts, and two-way coupling. The two individual banana source clips are retained for provenance.

## Tactile manipulation and contact

`tactile-puzzle-tubes-sim.mp4` keeps the left half of the [TAC puzzle and test-tube video](https://tac-corl.github.io/assets/videos/hero/1_puzzle_best_sim_tube_grid_14s.mp4): both stacked simulation views, at 1080 x 1200, with all 420 frames and the original 14-second timing. The full source URL, checksum, and crop coordinates are recorded in `manifest.json`.

`embeddedipc-1.mp4` is the user-provided real/simulation comparison of a robot placing a plate in a dish rack. Its original 1920 x 1080 file is preserved unchanged; the inline playback version is silent, 720p, and 30 fps.
