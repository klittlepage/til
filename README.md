# Today I learned

## 2019

### January

#### 01

There's a variety of tricks for fast modulo reduction when the modulus is a Mersenne prime. Two approaches are [here](https://www.mersenneforum.org/showthread.php?t=1955), and a third one leveraging SIMD instructions is [here](https://eprint.iacr.org/2010/338.pdf).

#### 02

Simple topological counting rules can [predict the mechanical stability of knots](https://science.sciencemag.org/content/367/6473/71).

Wombat feces are [cube shaped](https://www.bbc.com/news/world-australia-46258616).

[Eschatology](https://en.wikipedia.org/wiki/Eschatology) is the word for the part of theology concerned with the final events of history.

Platypodes are not the only [venomous mammal](https://en.wikipedia.org/wiki/Venomous_mammal).

#### 03

There's a rich history to a (now) well know approach to 2.5D rendering called [voxel space](https://en.wikipedia.org/wiki/Voxel_Space). [Sebastian Macke](https://github.com/s-macke/VoxelSpace) describes the history well.

The canonical book on missing data/data bias in general got an update in 2019: [Statistical Analysis with Missing Data](https://www.amazon.com/Statistical-Analysis-Missing-Probability-Statistics/dp/0470526793/ref=sr_1_1?keywords=Statistical+Analysis+with+Missing+Data&qid=1578112978&s=books&sr=1-1).

#### 04

Australia is deploying the military to fight the [2019-2020 bushfire season](https://www.nytimes.com/2020/01/04/world/australia/fires-military.html).

#### 05

[Deterministic databases](http://dbmsmusings.blogspot.com/2019/01/its-time-to-move-on-from-two-phase.html) guarantee that given a defined set of input requests only one final state is possible. This is a stronger guarantee than serializability that makes replication trivial.

#### 06

[Orthodromic distance](https://en.wikipedia.org/wiki/Great-circle_distance) is the shortest distance between two points on the surface of a sphere.

#### 07

The [first chosen-prefix collision for SHA-1](https://sha-mbles.github.io/) came out today.

#### 08

Google's [library for GIS](https://s2geometry.io/) has a [cool illustration](https://s2geometry.io/resources/earthcube) of how a single space-filling curve covers the globe.

#### 09

The [Rete algorithm](https://en.wikipedia.org/wiki/Rete_algorithm) allows for fast pattern matching when implementing rule-based systems.

#### 10

There's a fascinating [mind map of symmetries in physics](https://en.wikipedia.org/wiki/Exceptional_object#/media/File:Exceptionalmindmap2.png).

#### 11

The generalization of real numbers, complex numbers, and quaternions, is a [Clifford algebra](https://en.wikipedia.org/wiki/Clifford_algebra).

#### 12

The [Trivers–Willard hypothesis](https://en.wikipedia.org/wiki/Trivers%E2%80%93Willard_hypothesis) suggests that female mammals are able to adjust offspring sex ratio in response to their maternal condition.

#### 13

The tool used for generating [The Rust Book](https://doc.rust-lang.org/book/) is [mdbook](https://github.com/rust-lang/mdBook).

#### 14

The [Grossman-Stiglitz paradox](https://www.bloomberg.com/opinion/articles/2014-04-02/high-frequency-trading-may-be-too-efficient) refers to the observation that "if markets are efficient -- if market prices accurately reflect all the information in the world -- then there's no incentive for anyone to invest any time or money or effort into finding more information."

#### 15

A critical [security vulnerability](https://media.defense.gov/2020/Jan/14/2002234275/-1/-1/0/CSA-WINDOWS-10-CRYPT-LIB-20190114.PDF) in Windows [allowed for spoofing of ECC certificates](https://research.kudelskisecurity.com/2020/01/15/cve-2020-0601-the-chainoffools-attack-explained-with-poc/). The underlying cause had nothing to do with the cryptographic primitives themselves but highlighted an interesting property of ECC - constructing a private key $K'$ that matches the public key of another private key $K$ is trivial if you have control over the curve parameters.

#### 16

The US [struggled greatly with torpedo technology](https://www.historynet.com/us-torpedo-troubles-during-world-war-ii.htm) during WWII.

#### 17

The ```syscall/sysret``` instructions found in x86-64 are [10x faster than software interrupts](https://x86.lol/generic/2019/07/04/kernel-entry.html).

#### 18

LISP had a [wild ride](http://flownet.com/gat/jpl-lisp.html) at JPL.
