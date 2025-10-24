# Description
JobResQA is a QA benchmark over synthetic résumé-JD pairs designed to evaluate LLMs' machine reading comprehension for HR-specific applications. The dataset contains 581 question-answer (QA) pairs annotated over a set of 105 unique pairs
of résumé and JD. The résumés and JDs are derived from real-world data through a data synthesis pipeline that produces synthetic, anonymized, yet realistic versions. The QA pairs are annotated manually by two linguists following detailed guidelines to ensure quality and diversity. The entire dataset is multi-way parallel across five languages, English (en), Spanish (es), Italian (it), German (de), and Chinese. The translations are produced by an LLM-based pipeline with human-in-the-loop corrections.

You can find the data, in .tsv format, in the folder `jobresqa`.
