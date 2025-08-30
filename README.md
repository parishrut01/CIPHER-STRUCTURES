<h1 align="center">CIPHER-STRUCTURES</h1>
<h3 align="center">Where math meets cryptography — exploring structure, secrecy, and everything in between.</h3>

---

A personal research repository at the intersection of <i>mathematics</i>, <i>cryptographic theory</i>, and <i>zero-knowledge systems</i>.  
It contains curated notes, implementations, and experiments — from abstract algebra to working circuits — documenting the structural logic behind modern cryptographic primitives and privacy-preserving protocols.

---

## Roadmap

| Module       | Topic                                              | Description                                                                 |
|--------------|----------------------------------------------------|-----------------------------------------------------------------------------|
| `Let's Begin`| What is cryptography? Why it matters               | A beginner-friendly overview of cryptography and its role in secure systems. |
| `History`    | Classical ciphers, crypto timeline                 | From Caesar ciphers to public-key cryptography and modern ZK systems.      |
| `The Math`   | Sets, functions, logic, etc                        | We start with the basics and dive into advanced mathematical topics.       |
| `Crypto-Math`| Finite fields, elliptic curves, polynomials, hashes| Mathematical tools foundational to cryptographic systems.                  |
| `Proofs`     | Soundness, completeness, proof techniques          | How cryptographic proofs are constructed, verified, and reasoned about.    |
| `Extras`     | Resources                                          | Further reading, papers, courses, and curated external links.             |

---

## `Let's Begin`

> This module lays the foundation by answering the most essential questions: What is cryptography? Why do we need it? And how does it impact the digital world around us?
We begin with a conceptual overview of cryptography — not just as a tool for secrecy, but as a mathematical framework for ensuring confidentiality, integrity, authenticity, and trust. From securing your messages to powering digital currencies, cryptography is at the heart of modern information systems.
You’ll explore its core goals, its evolution alongside technology, and the problems it was designed to solve. No prior mathematical or technical background is assumed — this section is meant to provide intuitive insights before diving deeper.
Whether you're a curious beginner or brushing up before tackling more complex ideas, this module sets the stage for everything that follows.
---

## `History`

> For the module on [history](https://www.geeksforgeeks.org/computer-networks/history-of-cryptography/), we begin with classical ciphers like the [Caesar cipher](https://www.geeksforgeeks.org/ethical-hacking/caesar-cipher-in-cryptography/), [Vigenère cipher](https://www.geeksforgeeks.org/dsa/vigenere-cipher/), and the ingenuity of ancient cryptographers who relied on secrecy through obscurity.
> 
>Then we move into the era of mechanical cryptography, featuring systems like the [Enigma machine](https://brilliant.org/wiki/enigma-machine/), whose cracking shaped the outcome of World War II. Next comes the revolutionary shift to modern cryptography: the invention of [public-key cryptography](https://www.geeksforgeeks.org/computer-networks/public-key-encryption/), [RSA](https://www.geeksforgeeks.org/computer-networks/rsa-algorithm-cryptography/), [Diffie-Hellman](https://www.geeksforgeeks.org/computer-networks/diffie-hellman-key-exchange-and-perfect-forward-secrecy/), and the emergence of [digital signatures](https://www.geeksforgeeks.org/computer-networks/digital-signatures-certificates/) and [hash functions](https://www.geeksforgeeks.org/dsa/hash-functions-and-list-types-of-hash-functions/). Finally, we touch on the rise of [zero-knowledge proofs](https://www.geeksforgeeks.org/computer-networks/zero-knowledge-proof/), [blockchain](https://www.geeksforgeeks.org/ethical-hacking/blockchain-technology-introduction/), and cryptography’s role in decentralized systems.
>
> This historical lens doesn’t just show what came before — it reveals how each leap in cryptography responded to real-world needs and laid the groundwork for the tools we study today.

---

## `The Math`

> Before we can unlock the mechanics of cryptographic systems, we need to speak the language they’re built in: **Mathematics**.
>
> This module starts with the essentials:—
> 1. **Foundation**
 >> a. [Set Theory](https://www.geeksforgeeks.org/maths/set-theory/).
> >
 >> b. [Functions and Relations](https://www.geeksforgeeks.org/maths/relations-and-functions/).
> >
 >> c. [Logic](https://www.geeksforgeeks.org/maths/introduction-to-mathematical-logic/) and [Propositional Calculus](https://www.geeksforgeeks.org/engineering-mathematics/proposition-logic/).
> >
 >> d. Basic [combinatorics](https://www.geeksforgeeks.org/engineering-mathematics/combinatorics/) and [Proof techniques](https://www.geeksforgeeks.org/maths/mathematics-introduction-to-proofs/).
> 2. **Number Theory**
 >> a. [Prime factorization](https://www.geeksforgeeks.org/maths/prime-factorization/).
> >
 >> b. [Greatest Common Divisor (GCD)](https://www.geeksforgeeks.org/maths/greatest-common-divisor-gcd/), [Euclidean algorithm](https://www.geeksforgeeks.org/dsa/euclidean-algorithms-basic-and-extended/).
> >
 >> c. [Modular arithmetic](https://www.geeksforgeeks.org/engineering-mathematics/modular-arithmetic/).
> >
 >> d. [Euler’s theorem](https://www.geeksforgeeks.org/maths/eulers-theorem/) and [Fermat’s Little Theorem](https://www.geeksforgeeks.org/dsa/fermats-little-theorem/).
> >
 >> e. [Chinese Remainder Theorem](https://www.geeksforgeeks.org/maths/chinese-remainder-theorem/).
> >
 >> f. [Discrete logarithms](https://www.brainkart.com/article/Discrete-Logarithms_8433/).
> > 
 >> g. [Quadratic residues](https://mathworld.wolfram.com/QuadraticResidue.html).
> 3. **Abstract Algebra**
 >> a. [Groups theory](https://www.geeksforgeeks.org/engineering-mathematics/groups-discrete-mathematics/) ([cyclic groups](https://www.geeksforgeeks.org/engineering-mathematics/cayley-table-and-cyclic-group-mathematics/), [group homomorphisms](https://www.geeksforgeeks.org/engineering-mathematics/group-homomorphisms-and-normal-subgroup/), [orders](https://www.geeksforgeeks.org/engineering-mathematics/subgroup-and-order-of-group-mathematics/#order-of-group)).
> >
 >> b. [Rings theory](https://math.libretexts.org/Bookshelves/Combinatorics_and_Discrete_Mathematics/Applied_Discrete_Structures_(Doerr_and_Levasseur)/16%3A_An_Introduction_to_Rings_and_Fields/16.01%3A_Rings_Basic_Definitions_and_Concepts) and [Fields](https://math.libretexts.org/Bookshelves/Abstract_and_Geometric_Algebra/Rings_with_Inquiry_(Janssen_and_Lindsey)/02%3A_Fields_and_Rings/2.01%3A_Fields).
> >
 >> c. [Polynomials over finite fields](https://en.wikipedia.org/wiki/Polynomial_ring?utm_source=chatgpt.com#Over_finite_fields).
> >
 >> d. [Vector spaces](https://www.geeksforgeeks.org/maths/vector-space/).
> 4. **Linear Algebra**
 >> a. [Vectors](https://www.geeksforgeeks.org/maths/vector-algebra/) and [Matrices](https://www.geeksforgeeks.org/engineering-mathematics/matrices/).
> >
 >> b. [Determinants](https://www.geeksforgeeks.org/maths/what-is-determinant-of-a-matrix/), [rank](https://en.wikipedia.org/wiki/Rank_(linear_algebra)) and [null space](https://www.geeksforgeeks.org/machine-learning/null-space-and-nullity-of-a-matrix/).
> >
 >> c. [Linear independence](https://www.geeksforgeeks.org/maths/linear-independence/) and [basis](https://en.wikipedia.org/wiki/Basis_(linear_algebra)).
> >
 >> d. [Dot product ](https://mathworld.wolfram.com/DotProduct.html) and [inner product](https://mathworld.wolfram.com/InnerProduct.html)
> 4. **Probability & Information Theory**
 >> a. [Basic probability theory](https://www.geeksforgeeks.org/maths/probability-theory/).
> >
 >> b. [Random variables](https://www.geeksforgeeks.org/engineering-mathematics/random-variable/) and [distributions](https://en.wikipedia.org/wiki/Probability_distribution).
> >
 >> c. [Entropy](https://brilliant.org/wiki/entropy-information-theory/) and [mutual information](https://en.wikipedia.org/wiki/Mutual_information).
> 5. **Computational Mathematics**
 >> a. [Time and space complexity](https://www.geeksforgeeks.org/dsa/time-complexity-and-space-complexity/) ([Big O notation](https://www.geeksforgeeks.org/dsa/analysis-algorithms-big-o-analysis/)).
> >
 >> b. [Computational hardness assumptions](https://graphsearch.epfl.ch/en/concept/6158383) (e.g., factoring, discrete log).
> >
 >> c. [Randomized algorithms](https://www.geeksforgeeks.org/dsa/randomized-algorithms/).
> >
 >> d. [Hash functions](https://www.geeksforgeeks.org/dsa/hash-functions-and-list-types-of-hash-functions/) and [collision resistance](https://en.wikipedia.org/wiki/Collision_resistance) (through mathematical prespective).

---

## `Crypto-Math`

> The algebra beneath cryptography.  
Key topics:
- [Elliptic curve groups over finite fields](https://rareskills.io/post/elliptic-curves-finite-fields).
- [Weierstrass equations](https://mathworld.wolfram.com/WeierstrassEllipticFunction.html).
- [Polynomial commitments](https://rareskills.io/post/pedersen-polynomial-commitment).
- [Cryptographic hash functions](https://www.geeksforgeeks.org/competitive-programming/cryptography-hash-functions/).
- [Pairings](https://en.wikipedia.org/wiki/Pairing-based_cryptography) (e.g., bilinear pairings for zkSNARKs).

Hands-on intuition meets formal definitions, leading into cryptography friendly math.

---

## `Extras`

> A curated selection of learning materials:
- [Lattice Theory](http://boole.stanford.edu/cs353/handouts/book1.pdf) (post-quantum cryptography).
- https://www.youtube.com/playlist?list=PLBlnK6fEyqRgJU3EsOYDTW7m6SUmW6kII.
- https://www.youtube.com/playlist?list=PL2jrku-ebl3H50FiEPr4erSJiJHURM9BX.
- https://www.youtube.com/playlist?list=PL8Vt-7cSFnw29cLUVqAIuMlg1QJ-szV0K.
- https://medium.com/@barchitect/advanced-cryptography-primitives-group-finite-field-elliptic-curve-and-pairing-8489e296115d.
- https://www.britannica.com/science/modern-algebra/Rings.
- https://eprint.iacr.org/2021/571.
- https://mkowal2.github.io/posts/2020/01/understanding-mi/
- https://www.math.toronto.edu/swastik/courses/rutgers/finitefields-F19/intro.pdf.
- https://o1-labs.github.io/proof-systems/plonk/polynomial_commitments.html.

Stay updated, deepen context, or contribute!

---

## Connect

- Maintainer: Parishrut   
- Email: asp.eth.2025@gmail.com  

---


