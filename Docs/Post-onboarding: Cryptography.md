# Resources

## Introduction
Some literature and courses to get familiar with why cryptography is important and how it works.
- [The Moral Character of Cryptographic Work](https://web.cs.ucdavis.edu/~rogaway/papers/moral-fn.pdf)
- [Intro to Cryptography in Ethereum](https://medium.com/immunefi/intro-to-cryptography-and-signatures-in-ethereum-2025b6a4a33d)
- [New Directions in Cryptography by Diffie & Hellman](https://ee.stanford.edu/~hellman/publications/24.pdf)
- [Cypherpunks mailing list archive](https://mailing-list-archive.cryptoanarchy.wiki/)
- [Dan Boneh Online Cryptography Course](https://crypto.stanford.edu/~dabo/courses/OnlineCrypto/) [Coursera Link](https://www.coursera.org/learn/crypto)
- [Elliptic curve cryptography](https://github.com/bellaj/Blockchain/blob/6bffb47afae6a2a70903a26d215484cf8ff03859/ecdsa_bitcoin.pdf)
- [Polynomial commitment schemes](https://scroll.io/blog/kzg)


## ZK Proofs 
Proof systems are a powerful primitive used for scalability and privacy. On the protocol level, blockchains uses them for [verifiable off-chain computation](https://starkware.co/) and [data availability commitments](https://www.eip4844.com/). On the application side, proofs are used for [data privacy](https://personaelabs.org/posts/personae/), incomplete information in videogames such as Dark Forest's [fog of war](https://dfwiki.net/wiki/Fog_of_war), and program correctness! 
- [Anatomy of a STARK](https://aszepieniec.github.io/stark-anatomy/)
- [Definitive explanation of ZkSnarks](https://arxiv.org/pdf/1906.07221.pdf)
- [PCP theorem](https://www.cs.utexas.edu/~danama/XRDS.pdf)
- [Number thoery](https://explained-from-first-principles.com/number-theory/)
- [Zero knowledge canon](https://a16zcrypto.com/zero-knowledge-canon/)
- [Survey of proofs, arguments, and zero knowledge](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf)
- [Foundations of probalistic proofs by Alessandro Chiesa](https://people.eecs.berkeley.edu/~alexch/classes/CS294-F2020.html) 
- [Youtube videos from Alessandro's course](https://www.youtube.com/playlist?list=PLGkwtcB-DfpzST-medFVvrKhinZisfluC)
- [Everything STARKs!](https://twitter.com/EliBenSasson/status/1578380154476208131?s=20&t=IbMbwSUkuEShS8rXzkSTOA)
- [Bulletproofs](https://crypto.stanford.edu/bulletproofs/)
- [Awesome-ZK!](https://github.com/ventali/awesome-zk)
- [ZK Machine learning](https://github.com/worldcoin/awesome-zkml)
- [Ingopedia](https://github.com/ingonyama-zk/ingopedia/blob/main/README.md)

## Formal Verification of Arithmetic Circuits
- [Veridise](https://veridise.com/)
- [Kestrel Institute](https://www.kestrel.edu/)

## MPC
Multi party computation is a way to distribute cryptographic processes across multiple individuals. This lets you distribute authority across multiple parties and compute results while allowing parties to withold data. MPC is oftentimes used for privacy because it is more flexible than FHE and other schemes, although it is succeptible to collusion risk. Examples include [Penumbra](https://penumbra.zone/). [Lit Protocol](https://litprotocol.com/) uses MPC for access control!
- [Awesome MPC](https://github.com/rdragos/awesome-mpc)
- [Distributed Key Generation](https://cronokirby.com/posts/2022/10/dkgs-in-groups/)
- [TSS Explained](https://academy.binance.com/en/articles/threshold-signatures-explained)
- [Awesome TSS](https://github.com/ZenGo-X/awesome-tss)
- [BLS](https://hackmd.io/@benjaminion/bls12-381)
- [Interactive BLS tool](https://iancoleman.io/blsttc_ui/)


## FHE
**TFHE deep dive: ZAMA AI - Ilaria Chilloti**
  * [Part 1: Ciphertext types](https://www.zama.ai/post/tfhe-deep-dive-part-1?utm_source=tfhe_deep_dive_part_I&utm_medium=substack&utm_campaign=blogpost)
  * [Part 2: Encoding and linear ops](https://www.zama.ai/post/tfhe-deep-dive-part-2?utm_source=tfhe_deep_dive_part_I&utm_medium=substack&utm_campaign=blogpost)
  * [part 3: key switching and levelled multiplications](https://www.zama.ai/post/tfhe-deep-dive-part-3?utm_source=tfhe_deep_dive_part_3&utm_medium=substack&utm_campaign=blogpost)
  * [Part 4: programmable bootstrapping](https://www.zama.ai/post/tfhe-deep-dive-part-4)
  * **General**
    * [Encrypted search using FHE](https://medium.com/zama-ai/encrypted-search-using-fully-homomorphic-encryption-99cd163b94)
    * [Exploring FHE: Vitalik](https://notes.ethereum.org/@vbuterin/r19UMPTiI)
    * [ML and FHE](https://medium.com/zama-ai/the-r-evolution-of-fhe-485b54a6e69c) 

## Post Quantum Cryptography
- [Overview](http://pqcrypto.org/index.html)
- [How long until we need PCQ?](https://sam-jaques.appspot.com/quantum_landscape) 
- [Shor's Algorithm](https://quantum-computing.ibm.com/composer/docs/iqx/guide/shors-algorithm)
- [Grover's Algorithm](https://quantum-computing.ibm.com/composer/docs/iqx/guide/grovers-algorithm)

## Research Resources
- [IACR](https://eprint.iacr.org/)
- [Ingonyama](https://github.com/ingonyama-zk/papers)
- [Geometry](https://geometryresearch.xyz/notebook)
- [Delendum](https://delendum.xyz/writing)
- [The crypto behind crypto](http://ethanfast.com/top-crypto.html)
