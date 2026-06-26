# OTF-MLFF-Tg
## "On-the-Fly Machine-Learned Force Fields for High-Fidelity Polymer Glass Transition Simulations".

### Directory "structures" contains the initial structure used to build a machine-learning force field for its respective polymer.
```
OTF-MLFF-Tg/ 
├── structures/ 
│   └── polymer-\*/
│       ├── POSCAR 
│       ├── CONTCAR 
│       └── POSCAR-ss 
└── README.md
```
POSCAR: Initial structure

CONTCAR: Equilibrated structure after 200ps run (step size 0.4 fs).

CONTCARs were further used to build larger polymeric structures containing multiple chains to perform Tg simulation.

Each folder also contains the corresponding larger polymeric structure "POSCAR-ss", which is used as the starting structure for Tg simulations. The protocol followed is mentioned in the manuscript and SI.

The polymer smiles corresponding to each folder are as follows: \
polymer-1: [\*]CCC=C([\*])CCCCCCC \
polymer-2: [\*]CC([\*])OCCCCCCCC \
polymer-3: [\*]CC([\*])CCCCC \
polymer-4: [\*]CC([\*])CCC \
polymer-5: [\*]CC[\*] \
polymer-6: [\*]CC([\*])C \
polymer-7: [\*]CC([\*])CC(C)C \
polymer-8: [\*]CC([\*])C1CCCC1 \
polymer-9: [\*]C(c1ccccc1)C[\*] \
polymer-10: [\*]CC([\*])C1CCCCC1 \
polymer-11: [\*]CC([\*])(C)c1ccccc1 \
polymer-12: [\*]CC([\*])c1ccccc1C(=O)NC 
