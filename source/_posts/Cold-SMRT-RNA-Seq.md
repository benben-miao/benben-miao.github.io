---
title: Gene expression profile and co-expression network of pearl gentian grouper under cold stress by integrating Illumina and PacBio sequences
coverWidth: 1920
coverHeight: 1080
date: 2022-01-08
tags: Science
cover: https://benben-miao.gitee.io/image-cloud/BioBlog/paper1-figure9.png
---

<!-- <div style="background-color: #eeeeee; width: 120px; padding:5px 20px; border-radius: 3px;">Read More</div> -->
<!-- more -->

## 
#### Paper Citation
<div class="card">
<b>Gene expression profile and co-expression network of pearl gentian grouper under cold stress by integrating Illumina and PacBio sequences</b>

Miao, B. Ben, Niu, S. F., Wu, R. X., Liang, Z. B., Tang, B. G., Zhai, Y., et al. (2021). Gene expression profile and co-expression network of pearl gentian grouper under cold stress by integrating illumina and pacbio sequences. Animals 11, 1–25. doi:10.3390/ani11061745.
</div>

## 
#### Abstract
<div class="card">
Pearl gentian grouper (<i>Epinephelus fuscoguttatus</i> ♀ × <i>Epinephelus lanceolatus</i> ♂) is a fish of high commercial value in the aquaculture industry in Asia. However, this hybrid fish is not cold-tolerant, and its molecular regulation mechanism underlying cold stress remains largely elusive. This study thus investigated the liver transcriptomic responses of pearl gentian grouper by comparing the gene expression of cold stress groups (20 °C, 15 °C, 12 °C, and 12 °C for 6 hours) with that of control group (25 °C) using PacBio SMRT-Seq and Illumina RNA-Seq technologies. In SMRT-Seq analysis, a total of 11,033 full-length transcripts were generated and used as reference sequences for further RNA-Seq analysis. In RNA-Seq analysis, 3,271 differentially expressed genes (DEGs), two low-temperature specific modules (tan and blue modules), and two significantly expressed gene sets (profiles 0 and 19) were screened by differential expression analysis, weighted gene co-expression networks analysis (WGCNA), and short time-series expression miner (STEM), respectively. The intersection of the above analyses further revealed some key genes, such as PCK, ALDOB, FBP, G6pC, CPT1A, PPARα, SOCS3, PPP1CC, CYP2J, HMGCR, CDKN1B, and GADD45Bc. These genes were significantly enriched in carbohydrate metabolism, lipid metabolism, signal transduction, and endocrine system pathways. All these pathways were linked to biological functions relevant to cold adaptation, such as energy metabolism, stress-induced cell membrane changes, and transduction of stress signals. Taken together, our study explores an overall and complex regulation network of the functional genes in the liver of pearl gentian grouper, which could benefit the species in preventing damage caused by cold stress.
</div>

## 
#### SMRT-Seq full-length transcripts annotation
<div class="card">
A total of 9,380 (85.02%) full-length transcripts were successfully annotated (E-value < 1 E-10) using at least one of the five databases. Among them, 9,378 (85.00%), 8,378 (75.94%), 6,431 (58.29%), 6,247 (56.62%), and 6,734 (61.04%) full-length transcripts were annotated based on alignment to NR, SwissProt, KOG, GO, and KEGG databases, respectively.
</div>
<br/>
<img src="https://benben-miao.gitee.io/image-cloud/BioBlog/paper1-figure1.png" style="width:100%;">

Figure 1. Comprehensive functional annotation of full-length transcripts against NR, Swissprot, KOG, GO, and KEGG databases.

## 
#### Differential expression analysis of RNA-Seq
<div class="card">
The DEGs were identified between different temperature experimental groups. As demonstrated in Fig. 3, there were 901 (496 up- and 405 down-regulated), 1,271 (725 up- and 546 down-regulated), 1,330 (787 up- and 543 down-regulated), and 2,447 (1,243 up- and 1,204 down-regulated) genes shown to be differentially expressed in comparison to CT vs LT20, CT vs LT15, CT vs LT12, and CT vs LT12-6, respectively (Table S1, S2, S3, S4). According to the comparative analysis between control group and low temperature groups, 3,410 differentially expressed genes were screened. The Venn diagram showed that four comparisons shared 306 DEGs . Notably, in the comparisons of LT20 vs LT15, LT20 vs LT12, and LT20 vs LT12-6, there were a total of 431 (230 up- and 201 down-regulated), 799 (471 up- and 328 down-regulated), and 1,956 (1,064 up- and 892 down-regulated) DEGs, respectively. In addition, 668 (344 up- and 324 down-regulated), 1,465 (762 up- and 703 down-regulated), and 1,120 (577 up- and 543 down-regulated) DEGs were identified in comparison to LT15 vs LT12, LT15 vs LT12-6, and LT12 vs LT12-6, respectively. These results showed that more DEGs were screened along with the decrease of water temperature and the extension of cold stress time.
</div>

## 
#### Expression trend of genes with decreasing temperature gradient
<div class="card">
Statistically significant P-values were found in profiles 0 and 19, and they had more genes than other profiles (Fig. 4A). As shown in Fig. 4B, profile 0 had 1,344 consistently down-regulated genes, and most of them were down-regulated at the LT20 group. In con-trast, a total of 1,134 genes were consistently up-regulated in profile 19 (Fig. 4C), and most of them were up-regulated at the LT20 group. Subsequently, some genes maintained orig-inal expression levels after the first down- or up-regulation, whereas others were contin-uously down- or up-regulated in all gradient nodes.
</div>
<br/>
<img src="https://benben-miao.gitee.io/image-cloud/BioBlog/paper1-figure4.png">

Figure 4. Short time-series expression profiles based on the temperature gradient. (A) Twenty time-series expression profiles; (B) The expression trend of genes in profile 0; (C) The expression trend of genes in profile 19. The horizontal axis represents temperature gradient, and the longitude axis represents the level of gene expression (up-or down-regulation).

## 
#### Eigen modules and genes related to low temperature
<div class="card">
In this study, 23 modules were obtained based on the co-expression network analysis of 8,826 mRNAs (Fig. 6), and the gene number in each module ranged from 55 to 3,412 (Table 3). Among the 23 modules, only three were significantly associated with different temperatures. As shown in Fig. 7, ME turquoise, tan, and blue modules were positively correlated with CT (R=0.78, P=5e-04), LT12 (R=0.84, P=9e-05), and LT12-6 (R=0.95, P=5e-08) experimental groups, respectively. Of note, the number of genes in the ME tan module (133) and blue module (1,343) was considerably lower than those in the turquoise module (3,412).
</div>
<br/>
<img src="https://benben-miao.gitee.io/image-cloud/BioBlog/paper1-figure7.png">

Figure 7. Module-traits relationships. The horizontal axis represents trait groups (temperature gradient), and the longitude axis shows 23 modules. The color scale on the right shows mod-ule-trait (temperature) correlation from -1 (blue) to 1 (red), indicating low to high correlations.

## 
#### GO and KEGG enrichment analyses of key eigen modules
<div class="card">
The GO and KEGG enrichment analyses were performed on the above three modules to further explore the functions of genes in the temperature-related specific modules. The main GO enrichment terms (Fig. 8A-C), similar to the three modules, included cellular process, single-organism process, metabolic process, cell, cell part, membrane, binding, and catalytic activity. The KEGG enrichment analysis (Fig. 8D, E) showed that both tan and blue modules are mainly enriched in the adipocytokine, glucagon, FOXO, insulin, and apelin signaling pathways. Compared with the turquoise module (Fig. 8F), many bi-ological processes and pathways were inhibited under low-temperature conditions. In brief, as the water temperature decreased, gene expression activity also decreased, and only key genes were expressed to resist cold stress.
</div>
<br/>
<img src="https://benben-miao.gitee.io/image-cloud/BioBlog/paper1-figure8.png">

Figure 8. Enrichment analysis of temperature-related specific modules. A, B, and C showed GO enrichment analysis of blue, tan, and turquoise modules, respectively. D, E, and F showed KEGG enrichment analysis of blue, tan, and turquoise modules, respectively.

## 
#### The PPI networks of key eigen modules
<div class="card">
We further analyzed the PPI network analysis to find the hub and key genes with vi-tal regulatory effects in the three modules. Here, the turquoise module possessed 98 nodes and four hub genes (ppp1cb, NUPR2, GLTPD2, ISCA2); the blue module contained 70 nodes and two hub genes (KHDRBS1, PPP2R1A); whereas the tan module only included 33 nodes and three hub genes (Cebpd, CDKN1B, Zfp36l1) (Fig. 9). By calculating the con-nectivity and sum comparison of each edge, hub genes were identified that had the high-est connectivity within these three modules.
</div>
<br/>
<img src="https://benben-miao.gitee.io/image-cloud/BioBlog/paper1-figure9.png">

Figure 9. The PPI networks included turquoise, tan, and blue modules. (A) The PPI network of the turquoise module with 98 nodes and 200 edges; (B) The PPI network of ME tan module with 33 nodes and 200 edges; (C) The PPI network of ME blue module with 70 nodes and 200 edges. Hub genes were highlighted with red color as the background, and other genes were shown in green circles.

## 
#### RT-qPCR validation of the key genes
<div class="card">
The relative expression profiles of eight DEGs were validated through qRT-PCR. As demonstrated in Fig. 10, CYC, CYP24A1, EIF4E, F2, XBP1, and CDO1 were up-regulated, whereas DECR2 and MT-ND4 were down-regulated. Notably, all the expression profiles in the eight genes were consistent with the RNA-Seq results.
</div>
<br/>
<img src="https://benben-miao.gitee.io/image-cloud/BioBlog/paper1-figure10.png">

Figure 10. Validation of RNA-Seq results using RT-qPCR. The horizontal axis represents groups, and the longitude axis represents the relative expression level.

## 
#### Discussion

| Transcripts                                                                                                    | Genes                                                                         | LogFC  | KEGG Pathways                                                                                                                     |
|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------|--------|-----------------------------------------------------------------------------------------------------------------------------------|
| shibanyu_transcript_846                                                                                        | PCK1 (Phosphoenolpyruvate carboxykinase, cytosolic)                           | 12.37  | Glycolysis/Gluconeogenesis, AMPK signaling pathway, FoxO signaling pathway, Insulin signaling pathway, Glucagon signaling pathway |
| shibanyu_transcript_6873                                                                                       | ALDOB (Fructose-bisphosphate aldolase B)                                      | -14.17 | Glycolysis/Gluconeogenesis                                                                                                        |
| shibanyu_transcript_9393                                                                                       | FBP1 (Fructose-1,6-bisphosphatase 1)                                          | 2.01   | Glycolysis/Gluconeogenesis, AMPK signaling pathway, Insulin signaling pathway                                                     |
| shibanyu_transcript_9234                                                                                       | FBP2 (Fructose-1,6-bisphosphatase isozyme 2)                                  | 2.68   | Glycolysis/Gluconeogenesis AMPK signaling pathway, Insulin signaling pathway                                                      |
| shibanyu_transcript_599                                                                                        | G6PC (Glucose-6-phosphatase)                                                  | 1.02   | Glycolysis/Gluconeogenesis, AMPK signaling pathway, FoxO signaling pathway, Insulin signaling pathway, Glucagon signaling pathway |
| shibanyu_transcript_1763                                                                                       | CYP2J1 (Cytochrome P450 2J1)                                                  | -1.13  | Linoleic acid metabolism                                                                                                          |
| shibanyu_transcript_511                                                                                        | CYP2J2 (Cytochrome P450 2J2)                                                  | -1.69  | Linoleic acid metabolism                                                                                                          |
| shibanyu_transcript_1230                                                                                       | CYP2J6 (Cytochrome P450 2J6)                                                  | -1.55  | Linoleic acid metabolism                                                                                                          |
| shibanyu_transcript_7206                                                                                       | CPT1A (Carnitine O-palmitoyltransferase 1, liver isoform)                     | 4.73   | AMPK signaling pathway, Glucagon signaling pathway                                                                                |
| shibanyu_transcript_168                                                                                        | PCK2 (Phosphoenolpyruvate carboxykinase [GTP], mitochondrial)                 | 1.39   | AMPK signaling pathway, FoxO signaling pathway, Insulin signaling pathway, Glucagon signaling pathway                             |
| shibanyu_transcript_1860                                                                                       | HMGCR (3-hydroxy-3-methylglutaryl-coenzyme A reductase)                       | 3.19   | AMPK signaling pathway                                                                                                            |
| shibanyu_transcript_6395                                                                                       | DHCR7 (7-dehydrocholesterol reductase)                                        | 1.41   | Steroid biosynthesis                                                                                                              |
| shibanyu_transcript_4825                                                                                       | CYP24A1 (1,25-dihydroxyvitamin D(3) 24-hydroxylase, mitochondrial)            | 7.53   | Steroid biosynthesis                                                                                                              |
| shibanyu_transcript_371                                                                                        | SOAT1 (Sterol O-acyltransferase 1)                                            | 2.42   | Steroid biosynthesis                                                                                                              |
| shibanyu_transcript_1553                                                                                       | DHCR24 (Delta(24)-sterol reductase)                                           | 1.63   | Steroid biosynthesis                                                                                                              |
| shibanyu_transcript_4386                                                                                       | SGK1 (Serine/threonine-protein kinase Sgk1)                                   | 2.95   | FoxO signaling pathway                                                                                                            |
| shibanyu_transcript_397                                                                                        | STAT1 (Signal transducer and activator of transcription 1-alpha/beta)         | 1.50   | FoxO signaling pathway                                                                                                            |
| shibanyu_transcript_4950                                                                                       | CDKN1B (Cyclin-dependent kinase inhibitor 1B)                                 | 2.53   | FoxO signaling pathway                                                                                                            |
| shibanyu_transcript_5980                                                                                       | GADD45B (Growth arrest and DNA damage-inducible protein GADD45 beta)          | 3.23   | FoxO signaling pathway                                                                                                            |
| shibanyu_transcript_639                                                                                        | PPARα (Peroxisome proliferator-activated receptor alpha)                      | 3.62   | Glucagon signaling pathway                                                                                                        |
| shibanyu_transcript_1906                                                                                       | SOCS3 (Suppressor of cytokine signaling 3)                                    | 3.16   | Insulin signaling pathway                                                                                                         |
| shibanyu_transcript_2800                                                                                       | PPP1CC-a (Serine/threonine-protein phosphatase PP1-gamma catalytic subunit A) | 4.01   | Insulin signaling pathway                                                                                                         |
| shibanyu_transcript_229                                                                                        | SHC1 (SHC-transforming protein 1)                                             | 1.04   | Insulin signaling pathway                                                                                                         |
| shibanyu_transcript_8219                                                                                       | KRAS (GTPase KRas)                                                            | 1.45   | Insulin signaling pathway，FoxO signaling pathway                                                                                  |
| shibanyu_transcript_37                                                                                         | MKNK2 (MAP kinase-interacting serine/threonine-protein kinase 2)              | 2.55   | Insulin signaling pathway                                                                                                         |
| shibanyu_transcript_3250                                                                                       | EIF4E (Eukaryotic translation initiation factor 4E)                           | 4.14   | Insulin signaling pathway                                                                                                         |
| shibanyu_transcript_4069                                                                                       | EEF2 (Elongation factor 2)                                                    | 13.22  | AMPK signaling pathway                                                                                                            |

<div class="card">
<i>4.1. Metabolic processes associated with cold stress</i>

<i>4.2. Response of signal transductions to cold stress</i>

<i>4.3. Endocrine system and cold stress</i>
</div>
<br/>
<img src="https://benben-miao.gitee.io/image-cloud/BioBlog/paper1-figure13.png">

Figure 13. Glucagon signaling pathway (A) and insulin signaling pathway (B).

## 
#### Conclusion
<div class="card">
Based on liver transcriptome analyses, this study demonstrates that the cold-related genes of the pearl gentian grouper in response to cold stress are most significantly en-riched through carbohydrate metabolism, lipid metabolism, signal transduction, and en-docrine system pathways. These pathways divide into several other major categories, in-cluding energy metabolism, stress-induced cell membrane changes, and stress signals transduction. Moreover, we further screened out some core candidate genes closely related to cold stress in the above pathways, including PCK, ALDOB, FBP, G6pC, CPT1A, PPARα, SOCS3, PPP1CC, CYP2J, HMGCR, CDKN1B, and GADD45B. Among them, energy-related metabolic pathways and genes had higher expression levels under cold stress, suggesting that energy homeostasis plays a crucial role in the physiological adjustments of the pearl gentian grouper when exposed to the cold stress environment. The pathways and genes identified in this study extend our understanding of the mechanisms involved in the cold stress response in marine fishes and facilitate selective aquaculture breeding of cold-tolerant pearl gentian grouper.
</div>

## 
#### References
<div class="card">
1.Donaldson, M.R.; Cooke, S.J.; Patterson, D.A.; Macdonald, J.S. Cold shock and fish. J. Fish Biol. 2008, 73, 1491–1530, doi:10.1111/j.1095-8649.2008.02061.x.

2.Samaras, A.; Papandroulakis, N.; Costari, M.; Pavlidis, M. Stress and metabolic indicators in a relatively high (European sea bass, Dicentrarchus labrax) and a low (meagre, Argyrosomus regius) cortisol responsive species, in different water temperatures. Aquac. Res. 2016, 47, 3501–3515, doi:10.1111/are.12800.

3.Long, Y.; Li, L.; Li, Q.; He, X.; Cui, Z. Transcriptomic characterization of temperature stress responses in larval zebrafish. PLoS One 2012, 7, doi:10.1371/journal.pone.0037209.

...
</div>