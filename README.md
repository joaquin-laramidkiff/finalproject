# Phylogenetic Biology - Final Project

## Guidelines - you can delete this section before submission

OK, here we go.

# Revealing the phylogenetic position of the Hoatzin (Opisthocomidae) using novel calibrations of Bayesian analyses

## Introduction and Goals

Over the past thirty years, analyses of several large molecular and morphological datasets have illuminated the once obscure topology of the avian tree of life (e.g., Mayr and Clarke 2003; Ericson et al. 2006; Hackett et al. 2008; Jarvis et al. 2014; Prum et al. 2015; Suh et al. 2015; Kimball et al. 2019; Kuhl et al. 2020). Along with this revolution in data collection, new dating techniques have increasingly allowed for the origins of the diversity of modern birds to be pinpointed in time. Time calibrations using recently discovered fossil specimens (e.g., Prum et al. 2015; Field and Hsiang 2018; Field et al. 2020) have placed the divergence dates of the earliest extant birds in the latest Cretaceous (e.g., Field et al. 2020). However, fossil and molecular data have also converged to support the hypothesis that the majority of extant bird diversity developed in an explosive radiation just following the K-Pg mass extinction (e.g., Jarvis et al. 2014; Prum et al. 2015; Ksepka et al. 2017; Berv and Field 2018; Field and Hsiang 2018; Field et al. 2020).

Despite these advances, the origins of several engimatic bird groups remain poorly understood. The evolutionary origins of one group, the hoatzins (Opisthocomidae), have been particularly elusive (e.g., Hughes and Baker 1999; Jarvis et al. 2014; Prum et al. 2015; Kuhl et al. 2020). For over thirty years, resolving the relationships of this group among other birds has formed a central project in avian phylogenetics (e.g., Hughes and Baker 1999; Jarvis et al. 2014; Kuhl et al. 2020).

Frustratingly, analyses relying on different types of data (genomic sequences, transcriptomes, morphology, etc.) resolve hoatzins at very different positions within Aves. Several analyses have placed hoatzins at varying positions near the base of Passerea and Telluraves (Jarvis et al. 2014; Prum et al. 2015; Kimball et al. 2019; Kuhl et al. 2020). Affinities with turacos have also been suggested, although the evidence for this relationship has been thoroughly questioned (Field and Hsiang 2018). Some fossil evidence might indicate a possible affinity with Cariamiformes, a group of predatory terrestrial stalkers now restricted to the southern hemisphere (e.g., Mayr 2016); exquisite gut content preservation in some fossil skeletons of early-diverging cariamiforms also indicates these animals may have been herbivorous (Mayr and Richter 2011) as in modern hoatzin.

To date, there have been no studies that integrate morphological and biogeographic evidence from fossils with improved phylogenetic methods for molecular data to tackle the problem of the origins of the Opisthocomidae. The goal of our (C.D.B. and J.L.-M.) project is to use improved dating techniques to critically assess and compare different hypotheses for the phylogenetic affinities of the hoatzin. This work is intended to feature within a larger study lead by C.D.B, J.L-M., and our colleagues Meghan R. Forcellati and James R. Napoli at the American Museum of History, which is centered around two main goals: (1) using computed tomography to provide a detailed description of the partial skeleton of an Eocene bird from North America that shows a high number of osteological similarities with Opisthocomidae and (2) conducting a phylogenetic analysis of putatitive fossil hoatzin using an expanded morphological dataset that intensely samples fossil and extant taxa in groups with which previous workers have allied Opisthocomidae (Gruiformes, Strisores, Cariamiformes, Musophagidae, Galloanseres, Charadriiformes, derived Telluraves). Using improved dating techniques will allow us to apply information from reevaluation of the aforementioned fossil material to assess the differing hypothesis for hoatzin origins currently proposed in the literature.

We intend to have workflow proceed as follows. We will take advantage of the number of previously conducted Bayesian analyses of avian relationships by accessing trees produced from in three recent molecular phylogenies of birds (Jarvis et al. 2014; Prum et al. 2015; Kuhl et al. 2020). Using recently published occurrences of putative fossil opisthocomids (e.g., Mayr et al. 2011; Mayr and Pietri 2014) and age dates for the Willwood Formation specimen, we will provide updated calibrations for the origins of this clade. We intend to test different calibration results including and excluding the early fossil 'hoatzin' material, much of which is highly incomplete and allied with Opisthocomidae by features that each are more widely distributed among Aves (e.g., Mayr et al. 2011; Mayr and Pietri 2014). The age of the definite Miocene fossil hoatzin Hoazinoides (Miller 1953), which we also intend to redescribe as part of the larger project, will be used as a hard minimum calibration point for Opisthocomidae.

We intend to supplement these new age data specific to Opisthocomidae with additional novel calibrations of other Neornithine clades. In the past half-decade, several important fossils have been reported and reinterpreted as some of the oldest representatives early-diverging neornithine clades. For example, the recovery of the mostly complete skull and partial skeleton of Asteriornis from the Maastrichtian of Belgium provides a hard minimum age for the divergence of the Galloanseres, the most basal neognath clade, within the Late Cretaceous (Field et al. 2020). Reevaluation of an extensive collection of avian postcrania from the late Maastrichtian New Egypt and Hornerstown Formations of New Jersey (Brownstein et al. in review) further supports the hypothesis that Galloanserans were diversifying before the Cretaceous-Paleogene extinction. Reinterpretation of Paleogene fossils has confirmed that many extant neoavian clades, including mousebirds (Ksepka et al. 2017), gruiforms (cranes and relatives; Musser et al. 2019), turacos (Field and Hsiang. 2018), penguins (Slack et al. 2006; Mayr et al. 2017), strisoreans (Nesbitt et al. 2011; Ksepka et al. 2013; Chen et al. 2019), and cariamiforms (Mayr 2016), diverged early. Precise dates for individual sites and fossils will be taken from these studies and the literature if available. If not, calibrations will use the currently standard dates for the smallest interval on the geological time scale within which the fossils can be placed (i.e., if the fossil does not have precise dates but is from the Oligocene, we will use GTS dates for that epoch). Previously used fossil calibrations for the three selected phylogenies will be systematically assessed. If studies published more recently than the foundational phylogenies include older calibration dates for specific clades, fossil calibration data will be replaced with the newer calibrations. Our goal is to integrate these new data into the calibration of well-supported molecular trees and more confidently estimate the divergences times in and around Opisthocomidae.

We will time-calibrate the following tree topologies produced in the previously-noted studies: for Prum et al. (2015), the tree produced from the concatenated, Bayesian analysis; for Jarvis et al. (2014), the tree produced from the total-evidence nucleotide alignment partitioned by sequence type that had been analyzed with maximum likelihood under a GTR+GAMMA model, and for Kuhl et al. (2020), the 3’UTR transcriptome species tree. We will force BEAST to estimate edge lengths only by prohibiting the program from exploring topology space and apply birth–death speciation model with default priors following Prum et al. (2015), Field et al. (2020), and others. Molecular evolutionary rates are highly variable across different bird lineages. The uncorrelated relaxed clock (UCLN), used in Prum et al. (2015), and the Random local clock, both of which allow for rate heterogeneity among branches, are therefore the best two models to use (Drummond and Rambaut 2006; Drummond et al. 2006). Non-avian outgroups (e.g., Crocodylia in Prum et al. 2015) will be pruned following previous studies to remove high rate heterogeneity that might unreasonably affect age estimation.

## Methods


## Results


## Discussion


## References

[1] Mayr G, and Clarke JA. 2003. The deep divergences of neornithine birds: a phylogenetic analysis of morphological characters. Cladistics 19(6), 527-553.DOI: https://doi.org/10.1111/j.1096-0031.2003.tb00387.x

[2] Ericson PGP, et al. 2006. Diversification of Neoaves: integration of molecular sequence data and fossils. Biology letters 2(4), 543-547. DOI: 10.1098/rsbl.2006.0523

[3] Hackett SJ, et al. 2008. A phylogenomic study of birds reveals their evolutionary history. Science 320(5884), 1763-1768. DOI: 10.1126/science.1157704

[4] Jarvis ED et al. 2014. Whole-genome analyses resolve early branches in the tree of life of modern birds. Science 346(6215), 1320–1331. DOI: 10.1126/science.1253451

[5] Prum RO, et al. 2015. A comprehensive phylogeny of birds (Aves) using targeted next-generation DNA sequencing. Nature, 526(7574), 569–573. DOI: 10.1038/nature15697

[6] Suh A, et al. 2015. The dynamics of incomplete lineage sorting across the ancient adaptive radiation of neoavian birds. PLoS Biology 13(8), e1002224. DOI: https://doi.org/10.1371/journal.pbio.1002224

[7] Kimball RT, et al. 2019. A phylogenomic supertree of birds. Diversity 11(7), 109. DOI: https://doi.org/10.3390/d11070109

[8] Kuhl H, et al. 2020. An unbiased molecular approach using 3’UTRs resolves the avian family-level tree of life. Molecular Biology and Evolution, in press. DOI: https://doi.org/10.1093/molbev/msaa191

[9] Field DJ, and Hsiang AY. 2018. A North American stem turaco, and the complex biogeographic history of modern birds. BMC Evolutionary Biology 18(1), 102. DOI: https://doi.org/10.1186/s12862-018-1212-3

[10] Field DJ, et al. 2020. Late Cretaceous neornithine from Europe illuminates the origins of crown birds. Nature, 579(7799), 397-401. DOI: https://doi.org/10.1038/s41586-020-2096-0

[11] Ksepka DT, Stidham TA, and Williamson TE. 2017. Early Paleocene landbird supports rapid phylogenetic and morphological diversification of crown birds after the K–Pg mass extinction. Proceedings of the National Academy of Sciences 114(30), 8047-8052. DOI: https://doi.org/10.1073/pnas.1700188114

[12] Berv JS, and Field DJ. 2018. Genomic signature of an avian Lilliput effect across the K-Pg extinction. Systematic Biology 67(1), 1-13. DOI: https://doi.org/10.1093/sysbio/syx064

[13] Hughes JM, and Baker AJ. 1999. Phylogenetic relationships of the enigmatic hoatzin (Opisthocomus hoazin) resolved using mitochondrial and nuclear gene sequences. Molecular Biology and Evolution 16(9), 1300-1307.

[14] Mayr G. 2016. Osteology and phylogenetic affinities of the middle Eocene North American Bathornis grallator—one of the best represented, albeit least known Paleogene cariamiform birds (seriemas and allies). Journal of Paleontology 90(2), 357-374. DOI: https://doi.org/10.1017/jpa.2016.45

[15] Mayr G, and Richter G. 2011. Exceptionally preserved plant parenchyma in the digestive tract indicates a herbivorous diet in the middle Eocene bird Strigogyps sapea (Ameghinornithidae). Paläontologische Zeitschrift 85(3), 303-307. DOI: 10.1007/s12542-010-0094-5

[16] Mayr G, Alvarenga H, and Mourer-Chauviré C. 2011. Out of Africa: Fossils shed light on the origin of the hoatzin, an iconic Neotropic bird. Naturwissenschaften 98(11), 961-966. DOI: 10.1007/s00114-011-0849-1

[17] Mayr G, and De Pietri VL. 2014. Earliest and first Northern Hemispheric hoatzin fossils substantiate Old World origin of a “Neotropic endemic”. Naturwissenschaften 101(2), 143-148. DOI: https://doi.org/10.1007/s00114-014-1144-8

[18] Miller AH. 1953. A fossil Hoatzin from the Miocene of Colombia. Auk 70(4), 484–495. DOI: 10.2307/4081360

[19] Brownstein CD, Lara Midkiff JM, and Nash J. A diverse bird assemblage from the Cretaceous Atlantic coast and the rise of modern avifaunas. Papers in Palaeontology, in review (PALA-09-20-4888-OA).

[20] Musser G, Ksepka DT, and Field DJ. 2019. New material of Paleocene-Eocene Pellornis (Aves: Gruiformes) clarifies the pattern and timing of the extant gruiform radiation. Diversity 11(7), 102. DOI: https://doi.org/10.3390/d11070102

[21] Slack KE, et al. 2006. Early penguin fossils, plus mitochondrial genomes, calibrate avian evolution. Molecular Biology and Evolution 23, 1144–1155. DOI: 10.1093/molbev/msj124

[22] Mayr G, et al. 2017. A Paleocene penguin from New Zealand substantiates multiple origins of gigantism in fossil Sphenisciformes. Nature Communications 8(1), 1-8. DOI: 10.1038/s41467-017-01959-6

[23] Nesbitt SJ, Ksepka DT, and Clarke JA. 2011. Podargiform affinities of the enigmatic Fluvioviridavis platyrhamphus and the early diversification of Strisores (“Caprimulgiformes”+ Apodiformes). PLoS One 6(11), e26350. DOI: https://doi.org/10.1371/journal.pone.0026350

[24] Ksepka DT, et al. 2013. Fossil evidence of wing shape in a stem relative of swifts and hummingbirds (Aves, Pan-Apodiformes). Proceedings of the Royal Society B: Biological Sciences 280(1761), 20130580. DOI: https://doi.org/10.1098/rspb.2013.0580

[25] Chen A, et al. 2019. Total-evidence framework reveals complex morphological evolution in nightbirds (Strisores). Diversity 11(9),143.

[26] Mayr G, and De Pietri VL. 2014. Earliest and first Northern Hemispheric hoatzin fossils substantiate Old World origin of a “Neotropic endemic”. Naturwissenschaften 101(2), 143-148. DOI: https://doi.org/10.1007/s00114-014-1144-8

[27] Drummond AJ, and Rambaut A. 2007. BEAST: Bayesian evolutionary analysis by sampling trees. BMC Evolutionary Biology 7(1), 1-8.

[28] Drummond AJ, et al. 2006. Relaxed phylogenetics and dating with confidence. PLoS Biology 4(5), e88. DOI: https://doi.org/10.1371/journal.pbio.0040088.

