# bone-videos

Video files for bonemarketing.net. They used to live in `videos/` in bonemarketing/bone-marketing,
which made every site deploy take about 15 minutes.

- bonemarketing.net forwards `/videos/<path>` here, so links keep the same path.
- To add a video: put it under `videos/<client>/`, commit, push. Link it as
  `https://bonemarketing.net/videos/<client>/<file>.mp4` (the forward handles it).
- GitHub's limit is 100 MB per file and 2 GB per push.
