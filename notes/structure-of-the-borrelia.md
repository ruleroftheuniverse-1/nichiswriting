Brangulis et al 2024

structural biology study that uses X-ray crystallography to map a key enzyme in _Borrelia burgdorferi_ (the Lyme disease bacterium)

study examines FtsH 
	a conserved ATP-dependent metalloprotease 
		like a molecular shredder that: 
			recognizes damaged or unnecessary proteins, 
			unfolds them using energy from ATP, 
			degrades them with a zinc-based protease site 
		Without it, the bacterium dies.

Bb version of FtsH called BB0789
	hadn’t been structurally solved before this study
	known to be essential for infectivity in both ticks and mammals 
	researchers set out to map its structure and confirm whether it still behaves like a true FtsH enzyme
	
Bb is metabolically lazy 
	scavenges lipids, amino acids, and nucleotides from its hosts (instead of making them) 
		dependency means it needs an agile membrane protein system for transport and secretion
			but misfolded or unneeded proteins can clog the system. 
			FtsH is the cleanup crew.

Like other bacterial FtsH proteins, BB0789 has:
	- Two transmembrane α-helices that anchor it to the inner membrane.
	- A small periplasmic domain that helps it assemble and function.
	- A cytosolic AAA+ ATPase domain for unfolding substrates.
	- A zinc-dependent M41 peptidase domain that cuts them up.

authors focus on the soluble cytosolic portion (residues 146–639) bc membrane regions are notoriously hard to crystallize.

##Methods

They cloned the cytosolic part of the bb0789 gene into E. coli, expressed it, purified it, and then:
	- Crystallized the protein after removing the 6xHis tag.
	- Collected Se-Met X-ray diffraction data at 3.3 Å resolution.
	- Used AlphaFold to fill in flexible loops missing from the crystal map.
	- Performed ATPase and protease assays to confirm activity.

##Results
1. The structure
They successfully solved the crystal structure: PDB ID 7ZBH.
Six identical subunits form a hexameric ring, about 110 Å wide and 60 Å tall. 
	ring architecture is functionally essential because the central pore is where substrate proteins are threaded through, unfolded, and destroyed

Each monomer has:
	An AAA+ ATPase domain (the upper ring): bound to ADP in this structure.
	A zinc protease domain (the lower ring): with Zn²⁺ coordinated by His-His-Asp, the classic HEXXH-type motif.
	The two domains are connected by a flexible loop, which was partially invisible in the crystal due to motion but well predicted by AlphaFold.

2. Comparison and validation

They compared BB0789 to FtsH from Aquifex aeolicus, Thermotoga maritima, and Thermus thermophilus.
Structural alignment (RMSD ~1.7–3.0 Å) showed strong conservation 
	esp in the catalytic motifs:
		Walker A/B motifs (for ATP binding and hydrolysis),
		SRH (second region of homology, oligomerization/ATP coupling),
		FVG motif (substrate translocation),
		HEXXH motif (zinc protease).

In other words, BB0789 is a textbook FtsH.

3. Activity confirmation

colorimetric ATPase assay showed phosphate release (so it hydrolyzes ATP)
FITC-casein protease assay showed it breaks down protein substrate (so it’s catalytically active).
Together: functional, not just structural

##Conclusions

confirmed BB0789’s hexameric structure and enzymatic activity 
	proving it’s a genuine essential ATP-driven protease in B. b 
	Since it’s vital for the bacterium’s survival and infectivity, it could be a promising therapeutic target
		if we can selectively inhibit it without harming host mitochondrial FtsH

##Big-picture insight

paper bridges structural biology and pathogenesis at molecular level
3D fold of this enzyme literally encodes the bacterium’s ability to live, adapt, and infect 
good example of how evolution conserves a machine’s design but tweaks its control wiring for different organisms