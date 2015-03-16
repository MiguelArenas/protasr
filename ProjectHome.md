`ProtASR` is an evolutionary framework to reconstruct ancestral protein sequences accounting for structural constrains.

It is known that protein evolution is influenced by the protein structure. However, most of current phylogenetic frameworks do not implement structurally constrained substitution models of evolution due to their mathematical complexity.

We have recently developed a substitution model of protein evolution called "Meanfield" that accounts for the protein structure including negative design and that can generate site-specific evolutionary parameters that can be introduced into a maximum likelihood function. We already found that this model can better fit real protein evolution by computing maximum likelihood estimates (evaluated with the AIC criterion) and amino acid distribution across sites.

On the other hand, the reconstruction of ancestral proteins is applied for a variety of purposes such as the inference of centralized proteins (centralized vaccines) and the inference of ancestral enzymes (paleoenzymology). See,
Gao, F. et al. Consensus and ancestral state HIV vaccines. Science 2003, 299:1515-1518.
Arenas, M. and Posada, D. Computational Design of Centralized HIV-1 Genes. Curr HIV Res 2010, 8:613-621.
Perez-Jimenez, R. et al. Single-molecule paleoenzymology probes the chemistry of resurrected enzymes. Nat Struct Mol Biol 2011,18:592-596.

Importantly, the inferred proteins should be as realistic as possible.

`ProtASR` arises from these aims and presents a fast and accurate evolutionary framework to infer ancestral protein sequences accounting for structural constrains. ProtASR through the Meanfield model can generate ancestral proteins that are more stable than proteins generated with the classical empirical substitution models.


#### Download ####
Details to download `ProtASR` can be found at Wiki/ProtASR\_Download (https://code.google.com/p/protasr/wiki/ProtASR_Download).
The package is implemented in C and perl and can run on Linux and Mac OS.

#### Citation ####
ProtAST: An evolutionary framework for ancestral protein reconstruction under structural contrains. In preparation. Arenas M, Liberles D & Bastolla U. 2015.

#### Acknowledgments ####
MA want to thank the Spanish Government through the “Juan de la Cierva” fellowship JCI-2011-10452 and the European Molecular Biology Organization (EMBO) for the Short Term Fellowship 367-2013.

#### Help ####
Please, do not hesitate to contact us (miguelmmmab@gmail.com) for any question.
