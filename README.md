# Podcast tools
This repo keeps tracks of the tools and toolchains used to prepare Data Coffee podcast (mp3 files, shownotes and other artifacts).

### mp3Shownotes2Md
Tooling for exporting show notes (stored in id3 tag of mp3 file) to markdown file

### Docker

Build image:

$ docker build --tag chapters .

Add chapters to mp3 file (file should be **snd.mp3**):

$ docker run --rm -v $(pwd):/opt/data chapters