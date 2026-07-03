# Research Notes

This directory records how the public source corpus was distilled and how claims remain traceable.

## Corpus

- Parsed posts: 15,210
- Tagged longform sources: 11
- Distilled topic files: 11
- Main source types: public short posts, public longform articles, public podcast/article notes

The full raw corpus is not duplicated here. Instead, each distilled claim in `references/topics/`, `references/anti-patterns.md`, `references/signature-phrases.md`, and `references/honest-limits.md` carries source IDs such as `post_05022`, `x_1783679227738653102`, `zhihu_p1952345403925192806`, or `podcast_ep57`.

## Traceability Rules

1. Treat topic files as the primary research notes for runtime use.
2. Quote only claims with explicit source IDs.
3. If a source is not represented in the topic notes, do not infer a position from silence.
4. If an answer applies the extracted framework to a new situation, label it as inference.
5. For out-of-domain questions, consult `references/honest-limits.md` before answering.

## Topic Map

See `source-index.md` for per-topic source counts.
