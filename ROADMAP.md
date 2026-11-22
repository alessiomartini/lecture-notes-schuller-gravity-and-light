# Roadmap

## Setup
- [x] Repo skeleton (preamble, build, transcripts tool, empty main.tex)
- [x] Download captions / audio, run `tools/transcripts.py` (reads the shared download `lecture-notes-schuller-courses/materials/raw/C3`)
- [x] Pilot: first chapter written and compiled

## Gravity and Light (ch. 1-28, tutorials as sections)
- [x] Ch01 L01 Topology
- [x] Ch01 tutorial 1: Topology (section of chapter 1; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch02 L02 Topological Manifolds
- [x] Ch02 tutorial 2: Topological Manifolds (section of chapter 2; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch03 L03 Multilinear Algebra
- [x] Ch03 tutorial 3: Multilinear Algebra (section of chapter 3; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch04 L04 Differentiable Manifolds
- [x] Ch04 tutorial 4: Differentiable Manifolds (section of chapter 4; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch05 L05 Tangent Spaces
- [x] Ch05 tutorial 5: Tangent Spaces (section of chapter 5; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch06 L06 Fields
- [ ] Ch06 tutorial 6: Fields (section of chapter 6; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch07 L07 Connections
- [x] Ch07 tutorial 7: Connections (section of chapter 7; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [ ] Ch08 L08 Parallel Transport & Curvature
- [ ] Ch08 tutorial 8: Parallel Transport Curvature (section of chapter 8; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch09 L09 Newtonian spacetime is curved!
- [x] Ch10 L10 Metric Manifolds
- [x] Ch10 tutorial 9 & 10: Metric Manifolds (section of chapter 10; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch11 L11 Symmetry
- [x] Ch11 tutorial 11: Symmetries (section of chapter 11; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [ ] Ch12 L12 Integration on manifolds
- [ ] Ch12 tutorial 12: Integration (section of chapter 12; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch13 L13 Spacetime
- [x] Ch14 L14 Matter
- [x] Ch15 L15 Einstein Gravity
- [ ] Ch15 tutorial 14: sheet only, no video (section of chapter 15; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [x] Ch16 L16 Optical Geometry I (lecturer: Werner, not Schuller)
- [x] Ch17 L17 Optical Geometry II (lecturer: Werner, not Schuller)
- [ ] Ch18 L18 Canonical Formulation of GR I (lecturer: Giulini, not Schuller)
- [ ] Ch19 L19 Canonical Formulation of GR II (lecturer: Giulini, not Schuller)
- [ ] Ch20 L20 Cosmology - The early epoch
- [ ] Ch21 L21 Cosmology - The late epoch
- [ ] Ch21 tutorial 15: Cosmology (section of chapter 21; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [ ] Ch22 L22 Black Holes
- [ ] Ch22 tutorial 13: Schwarzschild Spacetime (section of chapter 22; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [ ] Ch23 L23 Penrose Diagrams
- [ ] Ch23 tutorial 16: Diagrams (section of chapter 23; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [ ] Ch24 L24 Perturbation Theory I
- [ ] Ch25 L25 Perturbation Theory II
- [ ] Ch25 tutorial 17: sheet only, no video (section of chapter 25; sheets: https://tales.mbivert.com/on-heraeus-winter-school-tutorials/)
- [ ] Ch26 L26 How quantizable matter gravitates
- [ ] Ch27 L27 Sources of gravitational waves (lecturer: Schutz, not Schuller)
- [ ] Ch28 L28 How to detect gravitational waves (lecturer: Schutz, not Schuller)

## Constructive gravity (ch. 29-35)
- [ ] Ch29 All spacetimes beyond Einstein (Obergurgl lectures), arXiv:1111.4824
- [ ] Ch30 How quantizable matter gravitates: a practitioner's guide, arXiv:1402.6548 (same title as lecture 26)
- [ ] Ch31 Constructive gravity: foundations and applications (MG15 review), arXiv:2003.09726
- [ ] Ch32 Constructive gravity, Causal Fermion Systems 2025 talk (YouTube GE9wGmhRBe4, 29:43)
- [ ] Ch33 Theories of Everything interview with Curt Jaimungal, 2025 (YouTube Bnh-UNrxYZg, 2:29:23, auto subtitles only)
- [ ] Ch34 Saarland 2021 talk "Die Struktur der Raumzeit" (YouTube 2vef2GqLJ7M, German, 2:07:26)
- [ ] Ch35 PIRSA 04110037 "Classical limit of quantum gravity in an accelerating universe" (2004, pirsa.org/04110037)

## Idee

## Decisioni e cose provate
- Tutorial 6 (C06-V02): no YouTube captions and no local audio, so section "Tutorial 6" of ch06 is a placeholder; write it after `tools/whisper.py` or captions exist.
- Ch08 (Parallel transport & curvature) not written yet (only C08-V02 tutorial transcript exists, no lecture transcript); ch07, ch09 and ch10 refer to it as "not yet written".
- Ch07: Schuller's index order slips and the sign in the normal-coordinates chart are flagged in coursenotes. Ch10: exercise 6 symmetries verification is in appA-exam.
- Ch06 lecture error flagged in a coursenote: the topology {pi^-1(U)} on TM is not the one making the charts homeomorphisms.

- Ch12 (Integration on manifolds) not written: no transcript for C12-V01 yet (whisper still running, `tools/transcripts.py` lists none); write it between ch11 and ch13, ch11 refers to it as chapter~
ef{ch:c12}.
- Ch11 tutorial: the sheet-11 embedding of S^2 was reconstructed from the metric components (not read); ch13: the lecture's bound "spatial velocity length < 1" needs the normalisation by epsilon^0(v), flagged; ch14: signs of the Lorentz force and of T_ab (Maxwell) not verified, as in the lecture.

- Ch15 tutorial 14 (sheet only, no video): the section is a stub listing what lectures 14 and 15 announce for it; the sheet itself was not read, so the item stays open. Ch15: the sign and normalisation of the cosmological term and the figure `10^100`/`10^120` are flagged `[?]`; the caption of lecture 15 garbles which sign of Lambda Einstein wanted.

- Ch17: lecturer confirmed as Werner (second half of lecture 16 after its break; the csv has "Werner?"). Mis-hearings of the captions in ch15-17: warsaw law = Poisson, Romanian = Riemannian, Gauss Binet/Bernay = Gauss-Bonnet, fin solid = Finsler, Marcus Savannah = Marcus Werner, Swat shield = Schwarzschild. Ch16: the stationary line element and the sign of dt were not legible on the captions and are reconstructed (`[?]`); Morse index slip of the lecturer corrected in ch17.

## Log
- 2026-11-22: ch15 (Einstein Gravity), ch16 and ch17 (Optical Geometry I and II, lecturer Werner) written from the captions; tutorial 14 not written (sheet only, no video).
- 2026-11-22: ch11 (Symmetry + tutorial 11), ch13 (Spacetime) and ch14 (Matter) written; ch12 skipped, no transcript yet (see Decisioni). Lecture slips flagged in coursenotes: ch13 spatial-velocity bound, ch14 Lorentz-force sign.
- 2026-11-22: ch01 (Topology + tutorial 1) and ch02 (Topological Manifolds + tutorial 2) and ch03 (Multilinear Algebra + tutorial 3) and ch04 (Differentiable Manifolds + tutorial 4) and ch05 (Tangent Spaces + tutorial 5) and ch06 (Fields, lecture only: tutorial 6 has no transcript, see ch06 section Tutorial 6) written from the captions; ch07 (Connections + tutorial 7), ch09 (Newtonian spacetime is curved) and ch10 (Metric manifolds + tutorial 9 & 10) written from the captions (ch08 skipped: no transcript yet; 	s in preamble now has stretchable glue so long timestamp chains do not overflow); transcripts.py now reads the shared C3 download.
- 2026-11-21: repo creato
