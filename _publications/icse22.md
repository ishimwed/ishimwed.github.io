---
title: "Dynaplex: Inferring Asymptotic Runtime Complexity of Recursive Programs"
collection: publications
permalink: /publication/icse22
excerpt: 'In this paper we present Dynaplex, a tool for the automatic inference of recurrence relations from execution traces, which are subsequently solved to determine the asymptotic complexity bounds of recursive programs.'
date: 2022-8-5 
venue: 'Proceedings of the 44th ACM/IEEE International Conference on Software Engineering: Companion Proceedings'
paperurl: 
citation: 'Ishimwe, D., Nguyen, T., & Nguyen, K. (2022, May). Dynaplex: inferring asymptotic runtime complexity of recursive programs. In Proceedings of the ACM/IEEE 44th International Conference on Software Engineering: Companion Proceedings (pp. 61-64).'
---
Automated runtime complexity analysis can help developers detect egregious performance issues. Existing runtime complexity analysis are often done for imperative programs using static analyses. In this demo paper, we demonstrate the implementation and usage of Dynaplex, a dynamic analysis tool that computes the asymptotic runtime complexity of recursive programs. Dynaplex infers recurrence relations from execution traces and solve them for a closed-form complexity bound. Experimental results show that Dynaplex can infer a wide range of complexity bounds (eg: logarithmic, polynomial, exponential, non-polynomial) with great precision (eg: O(nlog23) for karatsuba). A video demonstration of Dynaplex usage is available at https://youtu.be/t7dhwZ7fbVs. 
[Download paper here](https://dl.acm.org/doi/epdf/10.1145/3510454.3516853)