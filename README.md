# Gravity and Light (Schuller): lecture notes

LaTeX study notes of the *WE-Heraeus International Winter School on Gravity and Light* (Linz, Feb 2015): 28 lectures
(Schuller, plus guests Werner, Giulini and Schutz, marked as such) with their tutorials, and a final part on Schuller's
constructive-gravity talks and papers. One chapter per lecture, every point linked to the second of the video.

- Videos: YouTube playlist of the Winter School (ids in `lecture-notes/videos.tex`).
- Tutorial sheets: [re-hosted by mbivert](https://tales.mbivert.com/on-heraeus-winter-school-tutorials/); cited, linked and paraphrased only.
- Build: `cd lecture-notes && python build.py all` (latexmk + scroll book `build/book.pdf`).
- Transcripts: `python -I -X utf8 tools/transcripts.py` turns YouTube captions or whisper output in
  `materials/transcripts/raw/` into `materials/transcripts/CXX-VYY.txt` (C = chapter, V = video of the chapter);
  `tools/whisper.py` transcribes lectures without captions. `materials/` is gitignored (third-party material, never committed).

## Backup sources (checking only, never copied)
- Backup notes (checking only, never copied): Richie Dadhley, [notes on the Winter School](https://richie291.wixsite.com/theoreticalphysics/post/the-we-heraeus-international-winter-school-on-gravity-and-light), LaTeX [RichieDadhley/Winter-School-On-Gravity-and-Light](https://github.com/RichieDadhley/Winter-School-On-Gravity-and-Light). No licence stated: all rights reserved.

Full inventory of Schuller's material: `../lecture-notes-schuller-courses/SOURCES.md` (local).
All rights on the lectures belong to their authors; these are personal, non-commercial study notes.
