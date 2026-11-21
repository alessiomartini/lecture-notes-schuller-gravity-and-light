# Instructions for Claude: Schuller, Gravity and Light notes

@~/.claude/templates/lecture-notes/RULES.md
Setup copied from `../lecture-notes-schuller-geometric-anatomy` (which copies Brunton/Mehrling): same preamble
machinery, `build.py`, `scroll.py`. When in doubt, do as that repo does.

## Sources and how to use them
- The repo is **public**. `materials/` (transcripts, audio, PDFs, notes by others) is gitignored: check
  `git status` before every commit.
- One chapter per lecture (`chapters/chNN-<slug>.tex`), sections in the order of the lecture.
- Main source = the lecture itself: `materials/transcripts/CXX-VYY.txt` (`[m:ss] text`, from YouTube
  captions or local whisper). Paraphrase in clean English, fix mis-hearings. Mis-hearings found so far: (none yet, fill in as found).
  **Never drop content**: every definition, theorem, proof, example, remark, digression and student question goes
  in (side remarks in `aside`/`coursenote`, skippable material in `secondary`).
- Formal style: Definition / Theorem / Proof as on the blackboard, proofs in full. Ambiguous blackboard notation:
  reconstruct from context and the backup notes, mark `[?]` if unsure. Lecture wins over notes; note relevant
  differences in `secondary`.
- `\ts{C}{V}{m:ss}` on every point (C = chapter number, V = video of the chapter, normally 1), `\seg{C}{1}{text}` in the Sources box.
- Backup notes (Dadhley, `materials/backup/`; lectures 17-19 are empty there) only to check symbols and statements, never copied (no licence).
- Each chapter starts with Sources + a `reading` box pointing to the matching chapters of the other Schuller sets
  (Geometric Anatomy, Quantum, Mechanik) and to his papers where useful.
- Exercises: short in the text, long ones verbatim in `appendices/appA-exam.tex`; passages taken out of the text go
  to `\section*{Set aside}` at the chapter end. Chapter end: `keyconcepts` box.
- Chapter number = lecture number (ch01-ch28), then ch29-ch35 for the constructive-gravity part (Obergurgl, practitioner's guide,
  MG15, CFS 2025, TOE interview, Saarland 2021, PIRSA 2004). `\ts{C}{1}{m:ss}` for the lecture; tutorials are extra videos
  of the same chapter, `\ts{C}{2}{m:ss}` (then 3, ...), in the order of `materials/videos.csv`.
- **Guest lectures**: 16-17 Werner, 18-19 Giulini, 27-28 Schutz (the lecturer column of the csv is not sure for 17-19): say
  "lecturer: X, not Schuller" in the Sources box.
- **Tutorials** are sections of the chapter of the lecture they follow (T9 covers lectures 9 and 10, in ch10). Sheets 14 and 17 have no video.
  Sheets: cite and link https://tales.mbivert.com/on-heraeus-winter-school-tutorials/, paraphrase only (copyright), verbatim only in a local build.
- Lecture 26 and arXiv:1402.6548 share the title "How quantizable matter gravitates"; write one and cross-reference the other.

## Build and check
`cd lecture-notes && python build.py all`, then grep `build/main.log` for `\.tex:[0-9]+:`, `undefined`, `Overfull`
and look at the rendered pages. When writing LaTeX through the shell backslashes get mangled: use Edit/Write.
