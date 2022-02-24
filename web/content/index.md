+++
template = "page.html"
+++

LATTE '22 is a workshop co-located with [ASPLOS '22][asplos-22]. For examples
of previously presented papers, take a look at [LATTE '21][latte-21].
LATTE will take place on **March 1st, 2022**.

> LATTE is going to offer a hybrid attendance model. Participants will be able to attend either remotely or in-person. Table and plenary discussions will both use hybrid modality. Like the previous year, we invite participants to make use of GitHub discussion threads to ask questions from authors. Speakers of accepted papers will be provided with details on talks after acceptance.

## Registration

To attend LATTE please use this [Whova link][whova] to register:
- For in-person attendance: Register for the "Tuesday Workshops". This will only give you access to the Tuesday workshops. You can additionally register for ASPLOS from the same page.
- For remote attendace: Register for the "ASPLOS remote" option which will give you access to the entire ASPLOS program.


## *Draft* Program

| Time (CET) | Event |
|-------------|-------|
| 10–10:15am | Opening & Introductions |
| 10:15–11am | [Session 1](#session-1) |
| 11–11:30am | Coffee Break |
| 11:30am–12:00pm | [Session 2](#session-2) |
| 12:00–1:30pm | Lunch (on your own) |
| 1:30–2:30pm | Discussion |
| 2:30–3pm | [Session 3](#session-3) |
| 3–4pm | Keynote: [Andrew Ling (Groq)](#andrew-ling-groq-a-kerneless-approach-to-deep-learning-compilers) |
| 4–4:30pm | Coffee Break |
| 4:30–5pm | [Session 4](#session-4) |
| 5–6pm | Keynote: [Chris Leary (Google)](#chris-leary-google-x-istentialism-supercomputers-silicon-atoms-and-the-science-between) |

## Keynotes

### Andrew Ling (Groq): A Kerneless Approach to Deep Learning Compilers

With the recent decline of Moore’s Law, modern day architectures have exploded in order to keep up with the compute demands of today. With that, compiler flows and techniques have been at the forefront to support these new architectures.  The vast majority of compilers lean on customized flows and kernels to enable high-performance. This involves investing billions of dollars to create a robust kernel library where kernel developers create hand scheduled and vectorized “inner loops” that leverage the hardware primitives effectively.  Nvidia and Intel have the lead in this space and have invested thousands of engineering years to create a kernel library that will be difficult to match. By forcing the industry to stick with a kernel first approach, we are inadvertently limiting the amount of customization and breadth of functionality that could otherwise be achieved, and preventing innovation.

In contrast, the Groq architecture was designed with a software first mindset to avoid the need for manual kernel development and provide a fully automated compilation flow to map HPC and Neural Network models down to the architectural level. This is a strong divergence from the conventional approach and will open up opportunities for further innovation in the machine learning and scientific computing space.

We are able to achieve this level of automation by simplifying the primitive set on the Groq architecture and avoiding traditional approaches to vectorization, which often require “rediscovering” parallelization opportunities in the program and aligning those opportunities with the hardware structure.  Advantageously, we are able to decompose directly to specific hardware blocks on the architecture which yields extremely high efficiency because of the regularity of the architecture. Efficiency is a direct result of the design approach that Groq took by using the compiler to guide the architecture design. This software first approach to architecture design will be critical for the industry to move at a faster pace as compute demands continue to grow exponentially in the foreseeable future.

### Chris Leary (Google): X-istentialism: Supercomputers, Silicon Atoms, and the Science Between!

In this talk we discuss the increasing development and adoption of accelerators from the vantage point of a wide-eyed hyperscaler accelerator developer. This talk humbly proposes that an era of "Radical Co-design" or "Co-design 2.0" is upon us, as indicated by current observations and trends. To this end, we recap a decade of accelerator development work across XLA (cluster-capable ML compiler), JAX (staging/metaprogramming), and XLS (high level synthesis toolchain), with acceleration targets now identified at datacenter scale (i.e. Google Wide Profiling / "datacenter tax" workloads), and programs collaborating on open RTL-level tooling and open ASIC process nodes (Category X).

Many confluent factors make this a special time in computing: we've exited the "treadmill" where innovations failed to overtake CPU improvements -- accelerators with definitive specializations are now deployed at scale. Philosophy of science offers guidance on how we might expect "crises" (term of art) around expected improvement rate, scale, and growth to lead to advances in our thinking on computation and how this might dovetail with dominant programming models. As we "rebase" our thinking, we'll observe numerous challenges and open questions on how best to proceed and what avenues of investigation might be most fruitful. However, the undercurrent of progress will be secured through development of open tools and active investigation/discussion in the open and in the scientific community, underscoring the importance of LATTE and its focus.



## Papers

{{ program() }}


<div class="committee">

<div class="pc">
<h2> Program Committee </h2>

- Rachit Nigam, Cornell University
- Adrian Sampson, Cornell University
- Ang Li, Princeton
- Fabian Schuiki, SiFive
- Gus Smith, University of Washington
- Hanchen Ye, UIUC
- Jianyi Cheng, Imperial College London
- Jie Wang, Amazon
- Jin Yang, Intel
- John Demme, Microsoft
- Jonathan Balkind, UC Santa Barbara
- Jose Renau, UC Santa Cruz
- Katherine Lim, University of Washington
- Kevin Laeufer, UC Berkeley
- Kiran Kintali, MathWorks
- Leonard Truong, Stanford
- Licheng Guo, UCLA
- Ross Daly, Stanford
- Shail Dave, Arizona State University
- Stephen Neuendorffer, Xilinx
- Tobias Grosser, University of Edinburgh
- Zhiru Zhang, Cornell

</div>

<div class="organization">
<h2> Organizing Committee </h2>

- [Rachit Nigam](https://rachitnigam.com)
- [Adrian Sampson](https://adriansampson.net)
- [Zhiru Zhang](https://www.csl.cornell.edu/~zhiruz/)
- [Stephen Neuendorffer](https://sites.google.com/site/sneuendorffer/)

</div>
</div>

[snapl]: http://cs.brown.edu/~sk/Memos/Conference-Discussion-Format/
[hotcrp]: https://latte.cs.cornell.edu/
[sigplanconf]: https://www.acm.org/binaries/content/assets/publications/consolidated-tex-template/acmart.pdf
[asplos-22]: https://asplos-conference.org/
[latte-21]: https://capra.cs.cornell.edu/latte21/
[format-example]: https://github.com/cucapra/latte22/tree/main/camera-ready
[groq]: https://groq.com/
[whova]: https://whova.com/portal/registration/aicas_202202/
[asplos-reg]: https://whova.com/portal/registration/aicas_202202/
