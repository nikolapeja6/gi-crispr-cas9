# CRISPR-Cas9

**CRISPR** stands for ***Clustered Regularly Interspaced Short Palindromic Repeats***. This refers to the basis of the ‘guide system’ that finds the ‘target’ – the specific sequence of the DNA that is to be modified. **Cas9** stands for ***CRISPR-associated protein 9***, the protein that acts like a pair of molecular scissors, capable of cutting strands of DNA. CRISPR-Cas9 systems that target specific sequences can be produced relatively easily in a laboratory, or obtained in the form of commercially available kits that can be purchased online.[^2]

CRISPR technology is a simple yet powerful tool for editing genomes. It allows researchers to easily alter DNA sequences and modify gene function. Its many potential applications include correcting genetic defects, treating and preventing the spread of diseases and improving crops. However, its promise also raises ethical concerns.[^3]

A global overview or CRISPR with it's key features emphasized (and in everyday language) is in the video below.

<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/1BXYSGepx7Q" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Origin and usage in nature

Viruses attack cells by inserting their DNA into a cell and then using the cells native mechanisms to copy the viral DNA. This multiples the viral DNA and the cell effectively becomes a virus factory, producing more and more viruses.


{% include image.html url="https://opentextbc.ca/biology/wp-content/uploads/sites/96/2015/02/Figure_17_01_05.png" description="Influenza virus attacking a cell" %}

Some bacteria, such as Streptococcus pyogenes, have evolved a mechanism for fighting off viruses - CRISPR. These organisms use CRISPR-derived RNA and various Cas proteins, including Cas9, to foil attacks by viruses and other foreign bodies. They do so primarily by chopping up and destroying the DNA of a foreign invader. The picture below illustrates how CRISPR works.

{% include image.html url="https://i1.wp.com/sitn.hms.harvard.edu/wp-content/uploads/2014/07/Pak-Fig-1.jpg" description="Virus attacks a bacteria cell" %}


CRISPR is a specialized region of DNA with two distinct characteristics: the presence of **nucleotide repeats** (black, diamond shaped bits in the picture above) and **spacers** (squared, multi-colored parts). Repeated sequences of nucleotides (the building blocks of DNA) are distributed throughout a CRISPR region. Spacers are bits of DNA that are interspersed among these repeated sequences. When a virus attacks a bacteria, the bacteria analyzes the viral DNA and creates new spacer (basically a pattern of the viral DNA). The new spacer is added to the CRISPR region, which contains the spacers that were taken from viruses that previously attacked the organism. They serve as a bank of memories, which enables bacteria to recognize the viruses and fight off future attacks[^3]. The bacteria then forms separate CRISPR RNAs based on every spacer in the CRISPR region. The CRISPR RNA acts as a sentinel, and scans every DNA or RNA it comes across. If it finds a match, that means the particular generic material belongs to a virus, so it defends the bacteria by cutting the DNA strand and effectively destroying it. The Cas9 protein is the one that does the cutting. 

An interesting thing is that the bacterial DNA, with its CRISPR region, now has the viral target sequence (the inserted spacer). Does that mean that the CRISPR-Cas9 denfese mechanism will recognize the bacterial DNA as a threat and cut it? No, as there is a built-in safety mechanism, which ensures that Cas9 doesn't just cut anywhere in a genome. Short DNA sequences known as PAMs ("protospacer adjacent motifs") serve as tags and sit adjacent to the target DNA sequence. If the Cas9 complex doesn't see a PAM next to its target DNA sequence, it won't cut. This is one possible reason that Cas9 doesn't ever attack the CRISPR region in bacteria, according to a 2014 review published in Nature Biotechnology.[^3]


CRISPR was first demonstrated experimentally by Rodolphe Barrangou and a team of researchers at Danisco, a food ingredients company. In a 2007 paper published in the journal Science, the researchers used Streptococcus thermophilus bacteria, which are commonly found in yogurt and other dairy cultures, as their model. They observed that after a virus attack, new spacers were incorporated into the CRISPR region. Moreover, the DNA sequence of these spacers was identical to parts of the virus genome. They also manipulated the spacers by taking them out or putting in new viral DNA sequences. In this way, they were able to alter the bacteria's resistance to an attack by a specific virus. Thus, the researchers confirmed that CRISPRs play a role in regulating bacterial immunity.


Until 2017, no one really knew what this process looked like. In a paper published Nov. 10, 2017, in the journal Nature Communications, a team of researchers led by Mikihiro Shibata of Kanazawa University and Hiroshi Nishimasu of the University of Tokyo showed what it looks like when a CRISPR is in action for the very first time. The video which was a supplement of their paper "Real-space and real-time dynamics of CRISPR-Cas9 visualized by high-speed atomic force microscopy" (published in Nature Communications 8, Article number: 1430 (2017)) can be seen below.

<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/w2_JN1JntlU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Gene editing with CRISPR

In 2012, two pivotal research papers were published in the journals Science and PNAS, which helped transform bacterial CRISPR-Cas9 into a simple, programmable genome-editing tool. The studies, conducted by separate groups, concluded that Cas9 could be directed to cut any region of DNA. This could be done by simply changing the nucleotide sequence of crRNA, which binds to a complementary DNA target. In the 2012 Science article, Martin Jinek and colleagues further simplified the system by fusing crRNA and tracrRNA to create a single "guide RNA." Thus, genome editing requires only two components: a guide RNA and the Cas9 protein. 

"Operationally, you design a stretch of 20 (nucleotide) base pairs that match a gene that you want to edit," said George Church, a professor of genetics at Harvard Medical School. An RNA molecule complementary to those 20 base pairs is constructed. Church emphasized the importance of making sure that the nucleotide sequence is found only in the target gene and nowhere else in the genome. "Then the RNA plus the protein (Cas9) will cut — like a pair of scissors — the DNA at that site, and ideally nowhere else," he explained. [^3]


{% include image.html url="https://www.genecopoeia.com/wp-content/uploads/2014/08/Pathways-for-repair-of-DSBs.jpg" description="Pathways for repairing double-stranded breaks (DSBs) [^4]" %}

Once the DNA is cut, the cell's natural repair mechanisms kick in and work to introduce mutations or other changes to the genome. Two different processes can occur in order to fix the double-stranded break (DSB): **non-homologous end-joining (NHEJ)** or **homology-directed repair (HDR)**. NHEJ is an imprecise repair process and  involves gluing the two cuts back together. This method tends to introduce errors, as nucleotides are accidentally inserted or deleted, resulting in mutations, which could disrupt a gene. HDR is a precise repair process and is used mainly in editing the DNA sequence. With HDR, the break is fixed by filling in the gap with a sequence of nucleotides. In order to do so, the cell uses a short strand of DNA as a template. Scientists can supply the DNA template of their choosing, thereby writing-in any gene they want, or correcting a mutation.[^3] [^5]

The vide below is an animation of the homology-directed repair (HDR) process.
<div align="center">
<iframe src="https://player.vimeo.com/video/106957770" width="640" height="360" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>

The non-homologous end-joining (NHEJ) is illustrated in the video below, with a few other approaches:
 - By disabling the cutting functionality and adding an enzyme, CRISPR can introduce specific, targeted mutations on a DNA base without cutting the DNA strand.
 - Some researchers have been working on promoting gene transcription. They disabled the cutting functionality of Cas9, and adding transcriptional activators are added. Other researcher have been working on inactivating transcription.
 - An interesting usage of CRISPR is adding flouresent proteins to it, which then enables us to visualize the 3D architecture of the genome.   

<div align="center">
<iframe  width="560" height="315" src="https://www.youtube.com/embed/4YKFw2KZA5o" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Usage and limitations


CRISPR-Cas9 has become popular in recent years, mostly because the technology is easy to use and is about four times more efficient than the previous best genome-editing tool (called TALENS).

In 2013, the first reports of using CRISPR-Cas9 to edit human cells in an experimental setting were published by researchers from the Broad Institute of the Massachusetts Institute of Technology and Harvard. Studies using in vitro (laboratory) and animal models of human disease have demonstrated that the technology can be effective in correcting genetic defects. Examples of such diseases include cystic fibrosis, cataracts and Fanconi anemia, according to a 2016 article published in the journal Nature Biotechnology. These studies pave the way for therapeutic applications in humans.

"I think the public perception of CRISPR is very focused on the idea of using gene editing clinically to cure disease," said Neville Sanjana of the New York Genome Center and an assistant professor of biology, neuroscience and physiology at New York University. "This is no doubt an exciting possibility, but this is only one small piece." 

CRISPR technology has also been applied in the food and agricultural industries to vaccinate industrial cultures (for yogurt, for example) against viruses. It is also being used in crops to improve yield, drought tolerance and nutritional properties. Another potential application is to create **gene drives**. These are genetic systems, which increase the chances of a particular trait passing on from parent to offspring. Eventually, over the course of generations, the trait spreads through entire populations, according to the Wyss Institute. Gene drives can aid in controlling the spread of diseases such as malaria by enhancing sterility among the disease vector — female Anopheles gambiae mosquitoes — according to the 2016 Nature Biotechnology article. In addition, gene drives could also be used to eradicate invasive species and reverse pesticide and herbicide resistance, according to a 2014 article by Kenneth Oye and colleagues, published in the journal Science. 

{% include image.html url="http://discovermagazine.com/~/media/Images/Issues/2015/may/mosquito7.jpg" description="**Left**: One copy of the altered gene is inherited, leading to a 50 percent chance of passing it on per generation. **Right**: By altering both chromosomes, gene drives ensure both copies of the altered gene are inherited, leading to a 100 percent chance of passing it on. [^10]" %}

### Drawbacks

Even though it has a lot of positive points, CRISPR-Cas9 is not without its drawbacks.

"I think the biggest limitation of CRISPR is it is not a hundred percent efficient," Church told Live Science. Moreover, the genome-editing efficiencies can vary. According to the 2014 Science article by Doudna and Charpentier, in a study conducted in rice, gene editing occurred in nearly 50 percent of the cells that received the Cas9-RNA complex. Whereas, other analyses have shown that depending on the target, editing efficiencies can reach as high as 80 percent or more. 

There is also the phenomenon of **"off-target effects"**, where DNA is cut at sites other than the intended target. This can lead to the introduction of unintended mutations. Furthermore, Church noted that even when the system cuts on target, there is a chance of not getting a precise edit. He called this "genome vandalism".

The many potential applications of CRISPR technology raise questions about the ethical merits and consequences of tampering with genomes. In the 2014 Science article, Oye and colleagues point to the potential ecological impact of using gene drives. An introduced trait could spread beyond the target population to other organisms through crossbreeding. Gene drives could also **reduce the genetic diversity** of the target population. 

Since changes to human embryos and reproductive cells can be passed on to subsequent generations, using CRISPR technology to make germline edits has raised a number of **ethical concerns**.Variable efficacy, off-target effects and imprecise edits all pose safety risks. In addition, there is much that is still unknown to the scientific community. In a 2015 article published in Science, David Baltimore and a group of scientists, ethicists and legal experts note that editing human embryos raises the possibility of unintended consequences for future generations "because there are limits to our knowledge of human genetics, gene-environment interactions, and the pathways of disease". [^3]

Other ethical concerns are more nuanced. Should we make changes that could fundamentally affect future generations without having their consent? What if the use of germline editing veers from being a therapeutic tool to an enhancement tool for various human characteristics? 

<div align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/8b_d3RIJJmo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


[^3]: [What Is CRISPR?](https://www.livescience.com/58790-crispr-explained.html)
[^4]: [Pathways for repair of DSBs.jpg](https://www.genecopoeia.com/wp-content/uploads/2014/08/Pathways-for-repair-of-DSBs.jpg)
[^5]: [Genome editing: the road of CRISPR/Cas9 from bench to clinic, by Ayman Eid and Magdy M Mahfouz](https://www.ncbi.nlm.nih.gov/pubmed/27741224) 
[^8]: [Regulatory uncertainty over genome editing](https://www.nature.com/articles/nplants201411)
[^9]: [The Potential of the Combination of CRISPR-Cas9 and Pluripotent Stem Cells to Provide Human Organs from Chimaeric Pigs](https://www.researchgate.net/publication/277580331_The_Potential_of_the_Combination_of_CRISPRCas9_and_Pluripotent_Stem_Cells_to_Provide_Human_Organs_from_Chimaeric_Pigs)
[^10]: [Genetically Modifying Mosquitoes to Eliminate Disease](http://discovermagazine.com/2015/may/14-mosquito-modified)
[^11]: [Could someone please give me an estimate of using CRISPR/Cas9-gRNA technology for knocking out genes from crop species like Maize and Rice?](https://www.researchgate.net/post/Could_someone_please_give_me_an_estimate_of_using_CRISPR_Cas9-gRNA_technology_for_knocking_out_genes_from_crop_species_like_Maize_and_Rice3)
[^12]: [Genome Editing with CRISPRs, TALENs and ZFNs](https://www.biocompare.com/Editorial-Articles/144186-Genome-Editing-with-CRISPRs-TALENs-and-ZFNs/)