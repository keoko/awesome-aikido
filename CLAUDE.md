# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository

A content-only "awesome list" of Aikido video links. There is no code, build, lint or test tooling: the whole project is `README.md`. Commit directly to `main`.

## Structure of README.md

- A hand-maintained `## Contents` table of contents sits under the intro. It is not generated, so any heading you add, rename or remove must be mirrored there.
- Body hierarchy: `##` kyu grade (1st kyu, 2nd kyu) → `###` category (Suwari Waza, Tachi Waza, Ushiro Waza, Ken Suburi, Jo, Tanto Dori, Randori) → `####` attack (e.g. Shomen Uchi, Ryote Dori) → `#####` technique (e.g. Ikkyo, Tenchi nage). Ken Suburi puts each suburi at `#####` directly under `###`.
- Each technique heading is followed by a bullet list of video links.
- The 1st kyu section is introduced by a note that every technique is trained in OMOTE and URA, and that videos are chosen to show the full posture → attack → defense combination, not the technique in isolation. Pick videos with that in mind.

## Conventions

- Link format: `- [Video title](https://www.youtube.com/watch?v=ID)`, using the video's real YouTube title (fetchable via `https://www.youtube.com/oembed?url=<video url>&format=json`).
- The same technique name repeats across attacks and kyus (Ikkyo, Kote gaeshi, Kokyu nage...). Make sure a new video goes under the right kyu → category → attack before adding it.
- When the exact same technique (category + attack + technique) appears in more than one kyu, keep the videos only in its first occurrence (1st kyu) and make the later one a pointer line, e.g. `*Same as 1st kyu — see [Jo · 14-movement kata](#14-movement-kata).*`. Add new videos for it to the 1st kyu section.
- TOC anchors follow GitHub's slug rules: lowercase, punctuation stripped, spaces to `-`, and duplicate headings get `-1`, `-2`... in document order. Adding or removing a heading shifts the suffixes of later duplicates, so re-check the TOC links after structural changes.
- Headings and notes are in English with Japanese technique terms (`Free attack`, `14-movement kata`, `1st suburi`). Video titles stay as published, in whatever language.

## Video selection

Prefer videos from senseis in the Aikikai tradition, especially the Yasunari Kitaura lineage (e.g. Shu Kitaura, Raphael Arilla). Other teachers worth including: Christian Tissier, Etsuji Horii, Leonardo Sodre. Check the channel/author (the oEmbed `author_name`) before adding a video.
