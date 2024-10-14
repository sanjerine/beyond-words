# Beyond Words: Investigating Model Alignment on Hate Speech Classification

## Abstract

This study evaluates the effectiveness of the alignment of Large Language Models
(LLMs) in detecting hate speech. Explicit hate speech, defined by overt deroga-
tory language, is more easily classified using traditional machine learning models.
However, implicit hate speech, which relies on sarcasm, metaphor, and cultural
references, poses a significant challenge for these models. While LLMs offer
improved capabilities for implicit hate speech detection, proprietary and closed-
source models are often constrained by alignment practices that prioritize ethical
concerns over objectivity, potentially hindering their performance. Recent ad-
vancements in open-source, uncensored LLMs have brought them to competitive
levels with their censored counterparts, raising the question of whether uncen-
sored models, due to their reduced alignment, could serve as more objective and
effective classifiers. To explore this, we benchmark both censored and uncen-
sored LLMs on a hate speech dataset. Our findings indicate that while overall
performance between censored and uncensored models is comparable, important
distinctions emerge: censored models exhibit higher precision, while uncensored
models demonstrate higher recall. Combining these strengths, we propose the
use of ensemble methods that leverage both model types to achieve balanced
classifiers with moderate precision and recall, and the highest F1 scores, offering
a robust solution for automated hate speech detection. The results of this study
are expected to provide insights into the trade-offs between model alignment for
safety and their effectiveness in nuanced content moderation tasks such as hate
speech detection.

## Repository Structure

The repository contains two folders:
- **dissertation**: notebooks used for dissertation experiments, as part of the Honours Programme at UWA - dated October 2024.
- **latest** : which contains finalized, cleaned versions of experiment notebooks, in preparation for paper submission (approx 2024). This is currently still **in-progress**.

This report is submitted as partial fulfilment of the requirements for the Honours Programme of the Department of Computer Science and Software Engineering, The University of Western Australia, 2024
