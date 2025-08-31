<h1 align="center">CIPHER-STRUCTURES</h1>
<h3 align="center">Where math meets cryptography — exploring structure, secrecy, and everything in between.</h3>

---

A personal research repository at the intersection of <i>mathematics</i>, <i>cryptographic theory</i>, and <i>zero-knowledge systems</i>.  
It contains curated notes, implementations, and experiments — from abstract algebra to working circuits — documenting the structural logic behind modern cryptographic primitives and privacy-preserving protocols.

---

## Roadmap

|   Module        | Topic                                              | Description                                                                  |
|-----------------|----------------------------------------------------|------------------------------------------------------------------------------|
|  `Let's Begin`  | What is cryptography? Why it matters               | A beginner-friendly overview of cryptography and its role in secure systems. |
|  `History`      | Classical ciphers, crypto timeline                 | From Caesar ciphers to public-key cryptography and modern ZK systems.        |
|  `The Math`     | Sets, functions, logic, etc                        | We start with the basics and dive into advanced mathematical topics.         |
|  `Crypto-Math`  | Finite fields, elliptic curves, polynomials, hashes| Mathematical tools foundational to cryptographic systems.                    |
|  `ZERO`         | Zero-Knowledge                                     | Introduction to Zero-Knowledege proofs.                                      |
|  `Proofs`       | Soundness, completeness, proof techniques, types   | How cryptographic proofs are constructed, verified, and reasoned about.      |
|  `Extras`       | Resources                                          | Further reading, papers, courses, and curated external links.                |

---

## `Let's Begin`

 This module sets the stage by providing the most fundamental questions: What is cryptography? Why do we need cryptography? And how does cryptography shape the digital world we experience?

> We start with an abstract introduction to cryptography — not only as a mechanism for secrecy, but also as a mathematical construct for guaranteeing confidentiality, integrity, authenticity, and trust. From securing your messages to powering digital currencies, cryptography is at the heart of modern information systems. You’ll explore its core goals, its evolution alongside technology, and the problems it was designed to solve. No prior mathematical or technical background is assumed — this section is meant to provide intuitive insights before diving deeper.

Whether you are a curious beginner, or just reviewing in preparation for more difficult concepts, this module lays the groundwork for all that is to come.

---

## `History`

For the module on [history](https://www.geeksforgeeks.org/computer-networks/history-of-cryptography/).

> We begin with classical ciphers like the [Caesar cipher](https://www.geeksforgeeks.org/ethical-hacking/caesar-cipher-in-cryptography/), [Vigenère cipher](https://www.geeksforgeeks.org/dsa/vigenere-cipher/), and the genius of ancient cryptographers who relied on secrecy through obscurity.
> 
>Then we move into the era of mechanical cryptography, featuring systems like the [Enigma machine](https://brilliant.org/wiki/enigma-machine/), whose cracking shaped the outcome of World War II. Next comes the revolutionary shift to modern cryptography: the invention of [public-key cryptography](https://www.geeksforgeeks.org/computer-networks/public-key-encryption/), [RSA](https://www.geeksforgeeks.org/computer-networks/rsa-algorithm-cryptography/), [Diffie-Hellman](https://www.geeksforgeeks.org/computer-networks/diffie-hellman-key-exchange-and-perfect-forward-secrecy/), and the emergence of [digital signatures](https://www.geeksforgeeks.org/computer-networks/digital-signatures-certificates/) and [hash functions](https://www.geeksforgeeks.org/dsa/hash-functions-and-list-types-of-hash-functions/). Finally, we touch on the rise of [zero-knowledge proofs](https://www.geeksforgeeks.org/computer-networks/zero-knowledge-proof/), [blockchain](https://www.geeksforgeeks.org/ethical-hacking/blockchain-technology-introduction/), and cryptography’s role in decentralized systems.

This historical lens doesn’t just show what came before — it reveals how each leap in cryptography responded to real-world needs and laid the groundwork for the tools we study today.

---

## `The Math`

Before we can unlock the mechanics of cryptographic systems, we need to speak the language they’re built in: **Mathematics**.

This module starts with the essentials:
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
 >> e. [Eulet Totient function](https://www.geeksforgeeks.org/dsa/eulers-totient-function/).
> >
 >> f. [Chinese Remainder Theorem](https://www.geeksforgeeks.org/maths/chinese-remainder-theorem/).
> > 
 >> g. [Discrete logarithms](https://www.brainkart.com/article/Discrete-Logarithms_8433/).
> > 
 >> h. [Quadratic residues](https://mathworld.wolfram.com/QuadraticResidue.html).
> >
 >> i. [Modular inverses](https://www.geeksforgeeks.org/dsa/multiplicative-inverse-under-modulo-m/).
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
 >> d. [P vs NP problems](https://www.geeksforgeeks.org/dsa/p-vs-np-problems/).
> >
 >> e. [Hash functions](https://en.wikipedia.org/wiki/Hash_function) and [collision resistance](https://en.wikipedia.org/wiki/Collision_resistance) (a mathematical prespective).

---

## `Crypto-Math`

Key concepts:
> 1. [Elliptic curve groups over finite fields](https://rareskills.io/post/elliptic-curves-finite-fields).
> 2. [Weierstrass equations](https://mathworld.wolfram.com/WeierstrassEllipticFunction.html).
> 3. [Polynomial commitments](https://rareskills.io/post/pedersen-polynomial-commitment).
> 4. [Cryptographic hash functions](https://www.geeksforgeeks.org/competitive-programming/cryptography-hash-functions/).
> 5. [Pairings](https://en.wikipedia.org/wiki/Pairing-based_cryptography) (e.g., bilinear pairings for zkSNARKs).
  
Hands-on intuition meets formal definitions, leading into cryptography friendly math.

---

## `ZERO`

> In cryptography, [zero-knowledge](https://intensecrypto.org/public/lec_14_zero_knowledge.html) is an approach that allows one party (the prover) to prove to another party (the verifier) that a given argument is true without disclosing any further information other than the truth of the statement.  It protects privacy by certifying knowledge or validity without releasing any underlying data.  This concept, established in 1985, is crucial in strengthening security and privacy, notably in blockchain and authentication systems, as it allows verification without exposing critical information.

---

## `Proofs`

In this module we dive into the basic principles of zero-knowledge proofs.

> **Soundness:** The property that prevents a dishonest prover from convincing an honest verifier that a statement is true when it is actually false. A sound system ensures that if a prover cannot actually possess the information (the "secret") to make the statement true, the protocol will expose their attempt to cheat with a very high probability, thus protecting the system from false claims. 
>
> **Completeness:** The property that ensures an honest prover can always convince an honest verifier that a statement is true, provided the statement is actually true. This means if the statement being proven is valid, the proof process will successfully demonstrate its validity, making the verifier accept it.
>
> **Proof Techniques:** Cryptographic methods that allow a prover to demonstrate the truth of a statement to a verifier without revealing any information beyond the statement's validity itself. The core principles are completeness (an honest prover can convince an honest verifier), soundness (a dishonest prover cannot fool a verifier), and zero-knowledge (the verifier learns nothing but the truth of the statement). Key types include interactive ZKPs, which require multiple back-and-forth exchanges, and non-interactive ZKPs (like zk-SNARKs and Bulletproofs), which produce a single, self-contained proof.

**Types of Zero-Knowledge Proofs:**
> _Interactive Zero-Knowledge Proofs:_ These proofs involve multiple rounds of interaction between the prover and the verifier, with the verifier asking challenges that the prover must answer correctly.
> 
> _Non-Interactive Zero-Knowledge Proofs (NIZKs):_ These are more complex but allow for a single proof to be generated and verified later without further interaction. Notable examples include:
>> 1. zk-SNARKs (Succinct Non-Interactive ARguments of Knowledge): These create very small proofs that can be verified quickly.
>> 2. Bulletproofs: A type of ZKP that offers shorter proof sizes than traditional SNARKs while not requiring a trusted setup.
>> 3. zk-STARKs (Scalable Transparent ARguments of Knowledge): Offer greater transparency, as they do not require a trusted setup, making them more trustless. More scalable and robust against quantum computing attacks.
 
---

## `Extras`

A curated selection of learning materials:
- [Lattice Theory](http://boole.stanford.edu/cs353/handouts/book1.pdf) (post-quantum cryptography).
- https://www.youtube.com/playlist?list=PLBlnK6fEyqRgJU3EsOYDTW7m6SUmW6kII.
- https://www.youtube.com/playlist?list=PL2jrku-ebl3H50FiEPr4erSJiJHURM9BX.
- https://www.youtube.com/playlist?list=PL8Vt-7cSFnw29cLUVqAIuMlg1QJ-szV0K.
- https://medium.com/@barchitect/advanced-cryptography-primitives-group-finite-field-elliptic-curve-and-pairing-8489e296115d.
- https://www.britannica.com/science/modern-algebra/Rings.
- https://eprint.iacr.org/2021/571.
- https://mkowal2.github.io/posts/2020/01/understanding-mi/.
- https://www.math.toronto.edu/swastik/courses/rutgers/finitefields-F19/intro.pdf.
- https://o1-labs.github.io/proof-systems/plonk/polynomial_commitments.html.
- https://codethechange.stanford.edu/guides/guide_zk.html.
- https://rareskills.io/zk-book.
- https://www.helius.dev/blog/zero-knowledge-proofs-an-introduction-to-the-fundamentals

Stay updated, deepen concepts and create without limits.

---

## Connect

- Maintainer: Parishrut   
- Email: asp.eth.2025@gmail.com  

---


