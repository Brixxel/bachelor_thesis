# From Syntax to Semantics: A Framework for Semantic Utility Metrics in Data Anonymization
Bachelor Thesis | DHBW Mannheim | Author: Felix Niklas Regler

As Large Language Models become increasingly integrated into data workflows, the anonymiza-
tion of unstructured text has emerged as a crucial requirement for meeting modern privacy
regulations. While recent advances allow privacy risks to be quantified with growing precision,
the corresponding measurement of data utility has not kept pace. Current approaches rely
largely on syntactic heuristics, such as token overlap or generalization depth [1, 2], that offer
only a limited view of whether the meaning of a document is preserved or not.

A text may appear fragmented after heavy redaction yet still convey its core message, whereas
privacy-preserving paraphrasing may subtly shift meaning in ways that simple syntactic metrics
fail to detect [2]. This mismatch highlights the need for utility measures that are grounded in
semantics rather than surface form. This work seeks to formalize and validate this concept, pro-
viding a framework that could redefine utility assessment in privacy-preserving data publishing
(PPDP) and corporate data governance.
