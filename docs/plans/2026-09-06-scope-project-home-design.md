# SCOPE project homepage design

## Purpose

Reposition `scope.science` from a catalogue search interface to the public home
of the SCOPE research project. SCOPE explains and conducts the mathematical sky
survey; Resultary is the public search and record layer for its findings.

## Information architecture

1. Preserve the existing SCOPE wordmark and astronomical visual language.
2. Lead with the project mission and a concise explanation of SCOPE's scope.
3. Present SCOPE Survey and SCOPE Deep as paired, evolved research architectures.
4. Explain the test–audit–evolve loop without exposing implementation detail.
5. End with a distinct Resultary handoff that says where all SCOPE records can
   be searched and inspected.

The existing About, Survey, and Deep pages remain available. Legacy catalogue
and demonstration-record pages remain as unlinked static history and are not
added to the sitemap.

## Visual direction

The page uses refined editorial minimalism with generous negative space, the
existing warm paper palette, the telescope wordmark, and one dark “night”
section for the evolution loop. Observatory imagery gives the two architectures
distinct wide-field and deep-field identities. Resultary is introduced with a
restrained blue accent rather than borrowing its full brand.

## Accessibility and verification

The semantic `h1` remains in the document, as does the visible phrase “A
Mathematical Sky Survey.” Links are usable without JavaScript, external links
are labelled and isolated, all imagery has descriptive alternative text, and
reduced-motion preferences are respected. Verification includes desktop and
mobile screenshots, link checks, HTML semantics, and a deployed-page smoke test.
