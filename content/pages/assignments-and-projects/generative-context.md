---
content_type: page
parent_title: Assignments and Projects
parent_uid: 6e81c0bd-4e52-5a46-1f05-35f350963ca7
title: 'Project Sample: Generative Context-free Grammars'
uid: e0285a65-8bce-669a-777e-a93b6267e32d
---

_Courtesty of MIT student, used with permission._

For my final project, I made a system for defining context-free grammars (CFGs) and expanding a sequence of terminals into non-terminals using randomized productions. This contrasts with the more common activity of parsing a string of already-generated terminals into higher-level nonterminals,which is essentially the reverse process. A sequence of terminals can then be processed to produce some sort of output, such as a sound or a song. Using this system, complex definitions can be easily created as a series of productions, each of which maps a symbol to one or more probabilistically-weighted expansions, in order to create complex randomized, but structured, behavior.

Complete report ([PDF]({{< baseurl >}}/resources/mit21m_380s10_assn_ss_c))

Code files and sample audio outputs ([ZIP]({{< baseurl >}}/resources/assn_ss_c_files)) (This ZIP file contains 3 .py, 4 .yaml, and 2 .wav files). The audio files are a 1-second sound and a 4-second song.