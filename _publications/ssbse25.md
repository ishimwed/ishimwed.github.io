---
title: "Pathogen: LLM-Guided Fuzzing for Pathological Input Generation"
collection: publications
permalink: /publication/ssbse25
excerpt: 'In this paper we generate input leading to worst-case runtime execution using an LLM-guided fuzzing approach.'
date: 2025-11-15
venue: 'Proceedings of the International Symposium on Search-Based Software Engineering (SSBSE)'
paperurl: 
citation: 'Ishimwe, D., & Nguyen, K. (2025, November). LLM-Guided Fuzzing for Pathological Input Generation. In Proceedings of the International Symposium on Search-Based Software Engineering (SSBSE). Cham: Springer Nature Switzerland.'
---
Pathological inputs can trigger worst-case algorithmic behavior, leading to excessive resource consumption and revealing performance bottlenecks. Generating such inputs is difficult because they follow highly specific patterns that random testing or traditional fuzzing rarely uncovers. Existing fuzzing techniques either rely on domain-specific knowledge, which limits generality, or apply mutations on binary representations of inputs that produce predominantly invalid inputs.
We present PathoGen, a feedback-driven fuzzing framework that integrates LLMs into evolutionary search to efficiently discover pathological inputs. By leveraging LLMs for candidate generation, PathoGen achieves high-quality input without requiring domain-specific knowledge, such as
handcrafted grammars. An adaptive prompt template mechanism ensures robustness during input generation, while convergence tracking by input size directs computational resources toward those most likely to expose worst-case behaviors.
Evaluation across textbook algorithms and real-world applications shows that PathoGen uncovers expected theoretical complexity bounds, induces significant slowdowns in practical systems, and outperforms existing domain-independent fuzzers in efficiency and input validity while per-
forming comparably to domain-specific fuzzers within their specialized
domains.

