## Quantum physics explained to business folks

Coming from a business background with little knowledge of physics and working in the quantum computing industry, I have struggled with the surprising underlying concepts of this field of science.

This article explores how quantum physics emerged, its key principles, and the groundbreaking technologies it has enabled, as simply as possible, but not simpler than necessary!

### Introduction

The aim of quantum physics is to **explain the dynamics of elementary particles**, such as atoms, electrons, and photons.

Unlike classical physics, which governs the macroscopic world that we experience on a daily basis, quantum physics describes **the counterintuitive laws of the microscopic universe**.

![classical_mechanics_vs_quantum_mechanics](</img/img_2025-02-18-quantum-physics-explained/classical_mechanics_vs_quantum_mechanics.png>) 
*Source: [EWT project](https://energywavetheory.com/spacetime/mechanics/) — in this article I use the terms mechanics and physics interchangeably.*

Indeed, at the quantum scale, particles can exist in multiple states simultaneously, or become instantly connected across vast distances. The Nobel laureate and physicist Richard Feynman, one of the fathers of quantum computing, used to joke: “I think I can safely say that **nobody really understands quantum mechanics**”.

Yet, modelling these dynamics has led to **revolutionary technological advances**, from the invention of lasers to the latest breakthroughs in quantum computing.

From now, we’ll take a **chronological perspective** to better highlight the ruptures that led to the emergence of quantum physics.

### The limits of classical physics (before 1900)

The foundations of modern classical mechanics were developed from the 17th to the 19th century.

Based on the laws of motion and gravity formulated by **Isaac Newton** (end of the 17th century), as well as electromagnetism described by **James Clerk Maxwell** (mid-19th century), classical physics effectively explains phenomena at **everyday scales** — such how aircrafts fly or how electric current flows through a wire. It is still very effective and drives a lot of today’s innovations!

However, as scientists started to explore the world of elementary particles, **classical physics faced significant limitations** and several experimental results could not be explained by the theory at the time.

For instance, in the late 19th century, scientists attempted to **explain how objects emit radiation**. Classical physics theory (Rayleigh Jeans law) predicted that as objects became hotter, they would emit **an infinite amount of energy** at high frequencies (like ultraviolet light), which was not the case for stars or heated metal. This was later called the “**[ultraviolet catastrophe](https://en.wikipedia.org/wiki/Ultraviolet_catastrophe)**” (Paul Ehrenfest in 1911).

### The birth of quantum physics (first half of the 20th century)

In 1900, **Max Planck** suggested that **energy is not continuous but comes in small, fixed amounts called “quanta”**, rather than in any size we want [[1](http://www.ub.edu/hcub/hfq/sites/default/files/planck-energieverteilung.pdf)].

Though the “ultraviolet catastrophe” was about visible objects rather than microscopic particles, Planck’s discovery not only solved the problem but also paved the way for **understanding the behavior of particles at the tiniest scales**. He was awarded the Nobel Prize in 1918 for this work and that was **the birth of quantum physics**!

As a matter of fact, in 1905, **Albert Einstein** (Nobel 1921) expanded on Planck’s idea by applying it to light [[2](https://einsteinpapers.press.princeton.edu/vol2-trans/100)]. He explained a phenomenon called **the photoelectric effect**, where light shining on certain materials and at specific frequencies (such as ultraviolet light) causes them to release electrons. He understood that light isn’t just a wave with a frequency, but also behaves like particles i.e. discrete packets of energy called “photons” carrying a fixed amount of energy depending on the frequency. In other words, **light is quantized**! (This idea was not accepted until 1915)

Further discovery followed!

In 1913, **Niels Bohr** (Nobel 1922) proposed **a model of the atom** where electrons have specific energy levels, and they can “jump” between these levels by absorbing or emitting quanta of energy [3]. This model is now taught [in first class of high school in France](https://www.snes.edu/IMG/pdf/physique_annexe_2e_bo.pdf)!

![bohr_atomic_model](</img/img_2025-02-18-quantum-physics-explained/bohr_atomic_model.png>)
*Bohr’s atomic model (1913).*

Then, in 1923, **Louis de Broglie** (Nobel 1929) proposed **the wave-particle dualit**y, a concept suggesting that not only light (Einstein, 1911), but ALL quantum particles, like electrons, exhibit both wave-like and particle-like properties [[4](https://www.academie-sciences.fr/pdf/dossiers/Broglie/Broglie_pdf/CR1923_p507.pdf)], as shown by [the double-slit experiment](https://en.wikipedia.org/wiki/Double-slit_experiment).

Three years later, building on this idea, **Erwin Schrödinger** (Nobel 1933) introduced an equation that mathematically **describes how the wave of a quantum system evolves over time** [[5](https://journals.aps.org/pr/abstract/10.1103/PhysRev.28.1049)]. It does not predict the precise location of a particle in space but instead provides **the probability of finding the particle at various possible locations**. This is essential to understand how atoms and molecules interact together in complex systems!

And I could mention many other revolutionary scientific discoveries in quantum physics from the first half of the 20th century!

The bottom-line is that **it was a period of great scientific discovery**, with intense exchanges between brilliant physicists (such as the Bohr–Einstein debates), that redefined the fundamental laws of physics at the very small scale, and we’ll see how in the next part!

![fifth_solvay_physics_conference](</img/img_2025-02-18-quantum-physics-explained/fifth_solvay_physics_conference.jpg>)
*Attendees of the Fifth Solvay Physics Conference in 1927: 17 of the 29 people on this picture were or became Nobel Prize winners!*

### The two main principles of quantum physics

In this section, I will try to explain **the two main principles of quantum physics**: superposition and entanglement.

#### Superposition

First, **superposition** refers to the idea that a quantum particle can exist in multiple states at the same time ***until it is observed***.

Here, a few things must be clarified:
- A particle, such as an atom or a photon behaves by the law of quantum physics at such a small scale, so that you cannot observe it with your eyes.
- If you try to observe it (by using photodetectors or optical tweezers, for instance), you will **physically interfere with the quantum system** which introduces noise from the classical world (it’s called decoherence).
- In other words, it is not the fact that you “actively” or “consciously” look at the quantum system that causes it to lose its superposition!

Consequently, it is impossible to predict the exact position of a quantum system before measuring it. **Quantum physics is probabilistic**!

![superposition](</img/img_2025-02-18-quantum-physics-explained/superposition.png>)
*A quantum object is in superposition of states, with probabilistic positions.*

This principle inspired the famous thought experiment from **Schrödinger**, the cat in a box that is in a superposition of states: dead + alive!

#### Entanglement

Second, entanglement is a phenomenon where two (or more) particles become strongly linked, no matter how far apart they are. Once entangled, measuring the state of one particle will ***instantly*** determine the state of the other!

![entanglement](</img/img_2025-02-18-quantum-physics-explained/entanglement.png>)

This surprising principle was even famously called by Einstein as “spooky action at a distance”. Actually, **quantum entanglement strongly contradicted his theory of relativity**, which implies that an event at one location cannot cause an immediate effect at another location as causal influence is limited by the speed of light. This led Einstein to believe that quantum theory was incomplete as he (co-)formulated **the EPR paradox** (Einstein-Podolsky-Rosen paradox) in 1935 [[6](https://cds.cern.ch/record/405662/files/PhysRev.47.777.pdf)].

Still, **Alain Aspect’s experiments** in 1982 provided empirical evidence of quantum entanglement! He was awarded the Nobel prize in physics in 2022 for this work [[7](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.49.91)].

In theory, entanglement can happen at an infinite distance but, in practice, for large distances, the particles need to be perfectly isolated from the noise of the classical world (which causes “decoherence”) [using optical fibers](https://www.ll.mit.edu/news/quantum-repeaters-use-defects-diamond-interconnect-quantum-systems), for instance.

### The quantum revolution(s) (from 1947)

Many technologies that are indispensable today are the result of this knowledge such as:
- **transistors** (invented in 1947) rely on quantum mechanics to control the flow of electrical current through semiconductor materials,
- **silicon photovoltaic panels** (1954) harness the photoelectric effect (that was mathematically described by Einstein),
- **lasers** (1960) are based on the principle of stimulated emission (excited atoms or molecules emit coherent light).

This first wave of innovation leveraging quantum physics from the beginning of the 20th century was retrospectively considered by Alain Aspect as **the first quantum revolution**!

Then, as physics improved, the better understanding of the principles of quantum physics (superposition and entanglement), following Aspect’s experiment (1) and the ability to manipulate individual particles with improved instruments (2) led to **the second quantum revolution**.

Indeed, it is now possible to **trap an electron or an atom** with lasers to observe and control it. This capability leads to the development of **new quantum technologies** in the field of cryptography, telecommunications, sensing and, of course, computing!

### Conclusion

Despite its counterintuitive principles, quantum physics is probably the most fruitful scientific theory ever, [according to Alain Aspect](https://www.youtube.com/watch?v=OeZ_63iKPho&t=310s). Indeed, it revolutionised our understanding of the world at the microscopic scale, with real impact at everyday’s scale.

If the 20th century was particularly rich in science and innovations, as shown on the historical timeline below, I cannot wait to see what the 21st has in store.

Besides the enormous scientific and engineering challenges ahead to deliver the promises of the second quantum revolution, educating business people to the concepts under the hood will help to decipher the hype around the ambitious technologies being developed in the labs.

### Resources
- The “bible” from Olivier Ezratty ([Understanding Quantum Technologies](https://www.oezratty.net/wordpress/2024/understanding-quantum-technologies-2024/)), updated every year.
- The videos (in French) from ScienceEtonnante, such as “[Les inégalités de BELL & les expériences d’Alain ASPECT](https://www.youtube.com/watch?v=28UN70790Do)” (2020).
- [The Nobel Prize lecture from Alain Aspect](https://www.youtube.com/watch?si=XhSohbX-rpZB0BFp&v=SdE1cnsghH8&feature=youtu.be) (2022) is also very instructive!
- [A 2023 series of five articles](https://www.polytechnique-insights.com/en/columns/science/quantum-physics-explained-by-one-of-its-nobel-prize-laureat/) (featuring Alain Aspect) in Polytechnique Insights, the review of the Institut Polytechnique de Paris.

### Foundational papers of quantum physics

- [1] M. Planck (1900). “Zur Theorie des Gesetzes der Energieverteilung im Normalspektrum”, Verhandl. Dtsch. phys. Ges. 2 237.
- [2] Einstein, A. (1905). On a Heuristic Viewpoint Concerning the Production and Transformation of Light. Annalen der Physik, 17, 132–148.
- [3] Bohr, N. (1913). On the constitution of atoms and molecules. The London, Edinburgh, and Dublin Philosophical Magazine and Journal of Science, 26(151), 1–25.
- [4] de Broglie, L. (1923). “Radiations — Ondes et quanta”. Compt. Rend. 177, 507.
- [5] Schrödinger, E. (1926). An Undulatory Theory of the Mechanics of Atoms and Molecules. Physical Review, 28(6), 1049–1070.
- [6] Einstein, A., Podolsky, B., & Rosen, N. (1935). Can Quantum-Mechanical Description of Physical Reality Be Considered Complete? Physical Review, 47(10), 777–780.
- [7] Aspect, A., Grangier, P., & Roger, G. (1982). Experimental Realization of Einstein-Podolsky-Rosen-Bohm Gedankenexperiment: A New Violation of Bell’s Inequalities. Physical Review Letters, 49(2), 91–94.
