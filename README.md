# Levi Baruch

Researcher in Human Technology Interaction at Eindhoven, currently working on reproducability and open science. Specifically whether published datasets are actually reusable, and building tools to find out.
Experienced with making and training supervised machine learning models and making natural language data machine parsable.

Outside research: competitive (but still amateur) ballroom dancer and photographer — [levi.baruch.nl](https://levi.baruch.nl)

---

## Projects
**Dance-Face** *(Closed Source)*  
GDPR compliant web application that allows dancers to find their images based on a supplied image of themselves.

**[DataCheck](https://github.com/levibaruch/datacheck)** *(WIP)*  
DataCheck then takes any quantitative repository and classifies every file — determining what role each file plays (data, codebook, analysis script, output, etc.) using only filenames and ccontext. The result is a structured, machine-readable index of what's actually in each repository, reconstructed into PsychDS, an established standard.

**[PsychTrove](https://github.com/levibaruch/PsychTrove)** *(WIP, not yet deployed)*  
A dataset browser built on top of the Psych-DS structured output that DataCheck produces. The idea is to let you search and explore thousands of psychology datasets at the variable level — not just find papers, but find the actual variables measured across studies.

**[refexplorer](https://github.com/levibaruch/refexplorer)**  
Give it a BibTeX file and it maps out the citation network around those papers — finding what they cite, what cites them, and which papers are frequently co-cited together. Useful for finding relevant work you'd otherwise miss in a literature review.

**[papertrail](https://github.com/levibaruch/papertrail)**  
Citation verification. Point it at a paper and a folder of its references; it uses Claude to check whether each factual claim the paper makes is actually supported by what it cites. Produces a structured verdict per claim: accurate, slightly inaccurate, inaccurate, or unverifiable.

