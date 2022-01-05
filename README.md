# Photon-beetle_MAGMA
 Implementation of **PHOTON-beetle** algorithm for lightweight cryptography in MAGMA. The system was designed by the following researchers:
 
 * Zhenzhen Bao - Nanyang Technological University, Singapore 
 * Avik Chakraborti - NTT Secure Platform Laboratories, Japan 
 * Nilanjan Datta - Indian Statistical Institute, Kolkata, India 
 * Jian Guo - Nanyang Technological University, Singapore 
 * Mridul Nandi - Indian Statistical Institute, Kolkata, India 
 * Thomas Peyrin - Nanyang Technological University, Singapore 
 * Kan Yasuda - NTT Secure Platform Laboratories, Japan

and is one of the finalists for the <a href='https://csrc.nist.gov/Projects/lightweight-cryptography'>NIST call for lightweight cryptography</a>. You can find here the specifications on the NIST site or in the link <a href='https://csrc.nist.gov/CSRC/media/Projects/lightweight-cryptography/documents/round-2/spec-doc-rnd2/photon-beetle-spec-round2.pdf'>here</a>.  
 
 The system is composed by a family of authenticated sponge-based ciphers (they depends on a parameter *r*, said rate of message absorption) and a group of hash functions (also depending on *r*). The permutation used is *P_256* (referred also as <tt>`PHOTON_256`</tt>. In particular the functions submitted (and so the ones implemented in MAGMA) are:
 
 * <tt>`PHOTON-Beetle-AEAD`</tt> for r=32 and r=128
 * <tt>`PHOTON-Beetle-HASH`</tt> for r=32
 
 Students:
 Giulia Salvatori,
 Giacomo Borin,  
 **group YATTAMAN**

![202012715383927](https://user-images.githubusercontent.com/64214430/145833648-d91dc4fa-9f7d-4c37-8135-b99c2e2ad68a.jpg)
