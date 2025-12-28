# Projects

This folder contains **mini projects and learning outputs**: small, practical work that supports my understanding (not full-scale products).  
Compared to `/notes` (logs) and `/topics` (curated summaries), `/projects` is where I *build/try* things.

**TL;DR (ID):** `/projects` berisi percobaan kecil: perhitungan, simulasi, notebook, kode, diagram, atau eksperimen mini untuk mempraktikkan konsep yang dipelajari.

---

## What counts as a project here?

Examples:
- A small calculation sheet or derivation
- A simple simulation / model
- A short script or notebook (Python/Matlab)
- A diagram or workflow that I created
- A mini case study / toy dataset exploration

Non-goals:
- Large, long-term products (those will be split into milestones)
- Raw copied materials from courses/books

---

## Recommended structure

Create one folder per project:

- `projects/<project-name>/`
  - `README.md` (overview + results)
  - `src/` (code, optional)
  - `data/` (small data only, optional)
  - `assets/` (figures, images, optional)

Example:
- `projects/fault-kinematics-notes/`
- `projects/heat-conduction-toy-model/`
- `projects/well-log-basic-workflow/`

---

## Project README template (copy-paste)

Create: `projects/<project-name>/README.md`

```md
# Project Title

## Goal
Apa tujuan mini project ini?

## Background (short)
Konteks singkat: ini terkait topik apa, dan kenapa saya mengerjakannya?

## Inputs
- Data/software/tools yang dipakai (kalau ada)

## Method (high level)
- Langkah utama yang saya lakukan (ringkas)

## Output / Result
- Hasil utama (bisa berupa angka, plot, diagram, atau ringkasan temuan)

## Reflection
- Apa yang berhasil?
- Apa yang belum berhasil / next improvement?

## References
- Sumber yang dipakai (buku/paper/video/link)
