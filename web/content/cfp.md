+++
template = "page.html"
+++

## Important Stuff

Submit your **2-page position paper** via [HotCRP][]. Important dates:

- [HotCRP][] opens: **January 18, 2022**
- Paper submission:  **January 25, 2022**
- Author Notification: **February 8, 2022**
- Workshop: **March 1, 2022**

**Note.** The audience attending LATTE is already very specialized and does
not require motivating specialized hardware accelerators. We strongly encourage
authors to keep their introduction sections very focused and short and utilize
the space for more detailed technical content.

## News

- [Registration for ASPLOS][asplos-reg] (both in person and virtual) is available now.
- Andrew Ling, director of software engineer and machine learning at [Groq][groq], will give a keynote at LATTE '22.
- [Chris Leary](https://mobile.twitter.com/cdleary) will be giving a keynote at LATTE '22.

## Call for Participation

**Motivation.**
Hardware acceleration is a key part of combating the stagnation of hardware performance scaling. Implementing accelerators with state-of-the-art hardware design flows, such as traditional HDLs and current HLS tools, remains a specialized task requiring EE training, proprietary toolchains, and extremely slow compile-edit-run cycles. While traditional approaches *might* be appropriate for developing general-purpose CPUs that will ship millions of units, they are an impediment to popularizing acceleration for the “long tail” of applications that could benefit from special-purpose hardware. With new language designs and new techniques inspired by traditional compilers research, there is an opportunity to turn accelerator construction from a years-long enterprise into a weekend project.

**Scope.**
LATTE is a venue for discussion, debate, and brainstorming at the intersection of hardware acceleration and programming languages research. The focus is on new languages and tools that aim to let domain specialists, not just hardware experts, produce efficient accelerators. A full range of targets are in scope: ASICs (silicon), FPGAs, CGRAs, or future reconfigurable hardware. A wide variety of research topics are in scope including, but not limited to:

- Domain-specific languages for accelerator design
- Compilers for optimizing hardware designs
- Verification, testing, and debugging techniques
- Virtualization schemes for specialized & reconfigurable hardware

LATTE solicits short position papers that need not fit the mold of a traditional publication:

- Early, in-progress research snapshots
- Experience reports on building or deploying accelerators and the tools involved
- Essays advocating for or against a general approach
- Retrospectives on past efforts on tools, languages, and techniques for accelerator design
- Calls for solutions to open challenges in the area (questions without answers)
- Demonstrations of real systems (to be shown off in a live demo at the workshop)

### How to Participate

The primary goal of the workshop is to enable discussion. It will accept **2-page position papers**.
The workshop will allocate short time slots to the papers, each paired with a discussion following [SNAPL][]'s discussion format:
“table discussion” where small breakout groups will discuss the paper, followed by plenary Q&A.

Position paper submissions will undergo peer review by a program committee of interdisciplinary experts working on both high-level (languages, compilers, drivers) and low-level (circuit optimization, interconnect design) problems in the area.

**Formatting.** Papers should use the two-column [the formatting guidelines for SIGPLAN conferences][sigplanconf] (the `acmart` format with the `sigplan` two-column option) and not exceed 2 pages, excluding references. Review is single-blind, so please include authors' names on the submitted PDF.
We provide [a latex example][format-example] that contains the correct formatting.

Paper submission will is via [HotCRP][].
The accepted papers will not be published in a proceeding—PDFs will instead appear on the workshop's website.
