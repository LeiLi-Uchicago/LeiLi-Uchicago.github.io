---
layout: page
title: Projects
---

## Recent projects

Software tools and research platforms I have built for immunology, virology, and single-cell / spatial genomics. Click a project to explore its website, code, or publication.

<style type="text/css">
.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 22px;
    margin: 30px 0 10px;
}
.project-card {
    display: flex;
    gap: 16px;
    padding: 18px;
    border: 1px solid rgba(0, 0, 0, 0.09);
    border-radius: 14px;
    background: rgba(255, 255, 255, 0.55);
    box-shadow: 0 1px 3px rgba(0, 0, 0, 0.05);
    transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.project-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 22px rgba(0, 0, 0, 0.10);
}
.project-icon {
    flex: 0 0 76px;
    width: 76px;
    height: 76px;
    object-fit: contain;
    border-radius: 14px;
}
.project-body {
    display: flex;
    flex-direction: column;
    min-width: 0;
}
.project-body h3 {
    margin: 2px 0 6px;
    font-size: 1.18rem;
    line-height: 1.2;
}
.project-body p {
    margin: 0 0 12px;
    font-size: 0.92rem;
    line-height: 1.45;
    color: #555;
}
.project-links {
    margin-top: auto;
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
}
.project-links a {
    font-size: 0.8rem;
    font-weight: 600;
    text-decoration: none;
    padding: 3px 11px;
    border-radius: 999px;
    background: rgba(0, 123, 255, 0.10);
    color: #0a66c2;
    white-space: nowrap;
}
.project-links a:hover {
    background: rgba(0, 123, 255, 0.20);
    text-decoration: none;
}
.project-links .tag-muted {
    background: rgba(0, 0, 0, 0.06);
    color: #777;
    font-weight: 500;
}
</style>

<div class="project-grid" markdown="0">

  <div class="project-card">
    <img class="project-icon" src="/img/project/RVEAtlas_icon_transparent.png" alt="RVEAtlas logo">
    <div class="project-body">
      <h3>RVEAtlas</h3>
      <p>A comprehensive platform that tracks amino acid variation and clade evolution across respiratory viruses (RSV, influenza, SARS-CoV-2, and more).</p>
      <div class="project-links">
        <a href="https://leili-uchicago.github.io/RVEAtlas/">Website</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <img class="project-icon" src="/img/project/RSVrecon_icon_transparent.png" alt="RSVrecon logo">
    <div class="project-body">
      <h3>RSV Genomics</h3>
      <p>Screening clinically relevant genomic variations of respiratory syncytial virus (RSV) directly from NGS data.</p>
      <div class="project-links">
        <a href="https://github.com/stjudecab/RSVreconPy">RSVreconPy</a>
        <a href="https://github.com/stjudecab/RSVrecon">RSVrecon</a>
        <a href="https://onlinelibrary.wiley.com/doi/10.1111/irv.70203">Paper</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <img class="project-icon" src="/img/Spatial_icon.png" alt="Spatial Omics logo">
    <div class="project-body">
      <h3>Spatial Omics</h3>
      <p>Improving data interpretation for high-resolution spatial omics using computational approaches.</p>
      <div class="project-links">
        <a class="tag-muted" href="#">Code — in prep</a>
        <a class="tag-muted" href="#">Paper — in prep</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <img class="project-icon" src="/img/project/HTOreader_icon_transparent.png" alt="HTOreader logo">
    <div class="project-body">
      <h3>HTOreader</h3>
      <p>A hybrid single-cell demultiplexing strategy that increases both cell recovery rate and calling accuracy.</p>
      <div class="project-links">
        <a href="https://github.com/WilsonImmunologyLab/HTOreader">GitHub</a>
        <a href="https://academic.oup.com/bib/article/25/4/bbae254/7686601">Paper</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <img class="project-icon" src="/img/project/VGenes_icon_transparent.png" alt="VGenes logo">
    <div class="project-body">
      <h3>VGenes</h3>
      <p>An integrated graphical tool for efficient, comprehensive, and multimodal analysis of massive B-cell repertoire sequences.</p>
      <div class="project-links">
        <a href="https://wilsonimmunologylab.github.io/VGenes/">Website</a>
        <a class="tag-muted" href="#">Paper — in prep</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <img class="project-icon" src="/img/project/Librator_icon_transparent.png" alt="Librator logo">
    <div class="project-body">
      <h3>Librator</h3>
      <p>A platform for optimized sequence editing, design, and expression of influenza virus proteins.</p>
      <div class="project-links">
        <a href="https://wilsonimmunologylab.github.io/Librator/">Website</a>
        <a href="https://doi.org/10.1093/bib/bbac028">Paper</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <img class="project-icon" src="/img/project/LinQ-View_icon_transparent.png" alt="LinQ-View logo">
    <div class="project-body">
      <h3>LinQ-View</h3>
      <p>A single-cell analysis strategy that integrates RNA and ADT profiles for cell heterogeneity identification.</p>
      <div class="project-links">
        <a href="https://github.com/WilsonImmunologyLab/LinQView">GitHub</a>
        <a href="https://www.cell.com/cell-reports-methods/fulltext/S2667-2375(21)00104-1">Paper</a>
      </div>
    </div>
  </div>

  <div class="project-card">
    <img class="project-icon" src="/img/project/Cookie_icon_transparent.png" alt="Cookie logo">
    <div class="project-body">
      <h3>Cookie</h3>
      <p>Selecting representative samples from a single-cell atlas using k-medoids clustering.</p>
      <div class="project-links">
        <a href="https://wilsonimmunologylab.github.io/Cookie/">Website</a>
        <a href="https://www.frontiersin.org/articles/10.3389/fgene.2022.954024/full">Paper</a>
      </div>
    </div>
  </div>

</div>

## Past projects

---
### Dissecting the evolution of B cells against SARS-CoV-2 and Influenza viruses
- #Dugan, Haley L; #Stamper, Christopher; **#Li, Lei**; Changrob, Siriruk; Asby, Nicholas; Halfmann, Peter; Zheng, Nai-Ying; Huang, Min; Shaw, Dustin G; Cobb, Mari;  *Profiling B cell immunodominance after SARS-CoV-2 infection reveals antibody evolution to non-neutralizing viral targets*  **_Immunity_** 54, no. 6 (2021): 1290-1303. [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S1074761321001989)
- **#Li, Lei**; #Dugan, Haley L; #Stamper, Christopher; Lan, Linda Yu-Ling; Asby, Nicholas; Knight, Matthew; Stovicek, Olivia; Zheng, Nai-Ying; Madariaga, Maria Lucia; Shanmugarajah, Kumaran;   *Improved integration of single-cell transcriptome and surface protein expression by LinQ-View* **_Cell Reports Methods_**  1 (4), 100056 (2021) [Cell Press](https://www.cell.com/cell-reports-methods/fulltext/S2667-2375(21)00104-1)
- Guthmiller, Jenna J; Utset, Henry A; Henry, Carole; **Li, Lei**; Zheng, Nai-Ying; Sun, Weina; Vieira, Marcos C; Zost, Seth; Huang, Min; Hensley, Scott E;   *An egg-derived sulfated N-Acetyllactosamine glycan is an antigenic decoy of influenza virus vaccines*  **_Mbio_**  12, no. 3 (2021): e00838-21. [ASM Journals](https://journals.asm.org/doi/full/10.1128/mBio.00838-21)
- Siriruk Changrob, Yanbin Fu, Jenna Guthmiller, Peter Halfmann, **Lei Li**, Christopher Stamper, Haley Dugan, Molly Accola, William Rehrauer, Nai-Ying Zheng, Min Huang, Jiaolong Wang, Steven Erickson, Henry Utset, Hortencia Graves, Fatima Amanat, D Noah Sather, Florian Krammer, Yoshihiro Kawaoka, Patrick Wilson; *Cross neutralization of emerging SARS-CoV-2 variants of concern by antibodies targeting distinct epitopes on spike* **_ResearchSquare_** 2021 [Preprint](https://assets.researchsquare.com/files/rs-678247/v1/a3c7ee2f-64db-4cf6-9d57-41aae36cec6e.pdf?c=1626704791)
- Guthmiller, Jenna J; Stovicek, Olivia; Wang, Jiaolong; Changrob, Siriruk; **Li, Lei**; Halfmann, Peter; Zheng, Nai-Ying; Utset, Henry; Stamper, Christopher T; Dugan, Haley L;  *SARS-CoV-2 infection severity is linked to superior humoral immunity against the spike*    **_MBio_** 12, no. 1 (2021): e02940-20 [JSM](https://journals.asm.org/doi/full/10.1128/mBio.02940-20)
- Guthmiller, Jenna J; Han, Julianna; **Li, Lei**; Freyn, Alec W; Liu, Sean TH; Stovicek, Olivia; Stamper, Christopher; Dugan, Haley L; Tepora, Micah E; Bitar, Dalia J;  *First exposure to the pandemic H1N1 virus induced broadly neutralizing antibodies targeting hemagglutinin head epitopes*   **_Science Translational Medicine_**    2021 Vol. 13, Issue 596, eabg4535. DOI: 10.1126/scitranslmed.abg4535 [Science Translational Medicine](https://stm.sciencemag.org/content/13/596/eabg4535)
- Knight, Matthew; Changrob, Siriruk; **Li, Lei**; Wilson, Patrick C;     *Imprinting, immunodominance, and other impediments to generating broad influenza immunity* **_Immunological Reviews_** 2020 [Wiley](https://onlinelibrary.wiley.com/doi/full/10.1111/imr.12900)
- Guthmiller, Jenna J; Lan, Linda Yu-Ling; Fernández-Quintero, Monica L; Han, Julianna; Utset, Henry A; Bitar, Dalia J; Hamel, Natalie J; Stovicek, Olivia; **Li, Lei**; Tepora, Micah;   *Polyreactive Broadly Neutralizing B cells Are Selected to Provide Defense against Pandemic Threat Influenza Viruses*   **_Immunity_**  2020 [Pubmed](https://pubmed.ncbi.nlm.nih.gov/33096040/)
- Krammer, Florian; **Li, Lei**; Wilson, Patrick C;   *Emerging from the shadow of hemagglutinin: neuraminidase is an important target for influenza vaccination* **_Cell host & microbe_**   2019 [Pubmed](https://pubmed.ncbi.nlm.nih.gov/31951584/)

### Performing computational biology research to understand influenza genotype-phenotype corrolations
- **Li, Lei**; Chang, Deborah; Han, Lei; Zhang, Xiaojian; Zaia, Joseph; Wan, Xiu-Feng;  *Multi-task learning sparse group lasso: a method for quantifying antigenicity of influenza A (H1N1) virus using mutations and variations in glycosylation of Hemagglutinin*    **_BMC bioinformatics_**    2020 [BMC](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-020-3527-5)
- Han, Lei; **Li, Lei**; Wen, Feng; Zhong, Lei; Zhang, Tong; Wan, Xiu-Feng;     *Graph-guided multi-task sparse learning model: a method for identifying antigenic variants of influenza A (H3N2) virus*    **_Bioinformatics_**    2019 [PMC](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6298058/)
- Martin, Brigitte E; Bowman, Andrew S; **Li, Lei**; Nolting, Jacqueline M; Smith, David R; Hanson, Larry A; Wan, Xiu-Feng;   *Detection of antigenic variants of subtype H3 swine influenza A viruses from clinical samples* **_Journal of clinical microbiology_**  2017 [Pubmed](https://pubmed.ncbi.nlm.nih.gov/28077698/)

### Investigating origins and evolutionary pathways for avian influenza A (H5 and H7) viruses among domestic poultry
- **Li, Lei**; Bowman, Andrew S; DeLiberto, Thomas J; Killian, Mary L; Krauss, Scott; Nolting, Jacqueline M; Torchetti, Mia Kim; Ramey, Andrew M; Reeves, Andrew B; Stallknecht, David E;   *Genetic evidence supports sporadic and independent introductions of subtype H5 low-pathogenic avian influenza A viruses from wild birds to domestic poultry in North America*  **_Journal of virology_**   2018 [JVI](https://jvi.asm.org/content/92/19/e00913-18)
- **Li, Lei**; DeLiberto, Thomas J; Killian, Mary L; Torchetti, Mia K; Wan, Xiu-Feng;     *Evolutionary pathway for the 2017 emergence of a novel highly pathogenic avian influenza A (H7N9) virus among domestic poultry in Tennessee, United States*    **_Virology_**  2018 [Pubmed](https://pubmed.ncbi.nlm.nih.gov/30236990/)
- #Zhang, Xiaojian; #Sun, Hailiang; #Cunningham, Fred L; **#Li, Lei**; Hanson-Dorr, Katie; Hopken, Matthew W; Cooley, Jim; Long, Li-Ping; Baroch, John A; Li, Tao;  *Tissue tropisms opt for transmissible reassortants during avian and swine influenza A virus co-infection in swine* **_PLoS Pathogens_**    2018 [PLoS Pathogen](https://journals.plos.org/plospathogens/article?id=10.1371/journal.ppat.1007417)
- Lee, Dong-Hun, Mary Lea Killian, Thomas J. Deliberto, Xiu-Feng Wan, **Li Lei**, David E. Swayne, and Mia Kim Torchetti. *H7N1 Low Pathogenicity Avian Influenza Viruses in Poultry in the United States During 2018*. **_Avian Diseases_** 65, no. 1 (2021): 59-62. [Avian Diseases](https://meridian.allenpress.com/avian-diseases/article-abstract/65/1/59/445119/H7N1-Low-Pathogenicity-Avian-Influenza-Viruses-in)

### Imprinting of repeated influenza A/H3 exposures on antibody quantity and antibody quality
- #Kosikova, Martina; **#Li, Lei**; Radvak, Peter; Ye, Zhiping; Wan, Xiu-Feng; Xie, Hang;   *Imprinting of repeated influenza A/H3 exposures on antibody quantity and antibody quality: implications for seasonal vaccine strain selection and vaccine performance* **_Clinical infectious diseases_**  2018 [Pubmed](https://pubmed.ncbi.nlm.nih.gov/29672713/)
- Xie, Hang; **Li, Lei**; Ye, Zhiping; Li, Xing; Plant, Ewan P; Zoueva, Olga; Zhao, Yangqing; Jing, Xianghong; Lin, Zhengshi; Kawano, Toshiaki;   *Differential effects of prior influenza exposures on H3N2 cross-reactivity of human postvaccination sera*  **_Clinical Infectious Diseases_**  2017 [Pubmed](https://pubmed.ncbi.nlm.nih.gov/28369230/)

### Plant Poly(A) Site and Ortholog Identification Algorithm and Data Visualization Research
- **Li, Lei**; Ji, Guoli; Ye, Congting; Shu, Changlong; Zhang, Jie; Liang, Chun;    *PlantOrDB: A genome-wide ortholog database for land plants and green algae*    **_BMC plant biology_** 2015 [Pubmed](https://pubmed.ncbi.nlm.nih.gov/26112452/)
- Ji, Guoli; **Li, Lei**; Li, Qingshun Q; Wu, Xiangdong; Fu, Jingyi; Chen, Gong; Wu, Xiaohui;   *PASPA: a web server for mRNA poly (A) site predictions in plants and algae*    **_Bioinformatics_**    2015 [Oxford Press](https://academic.oup.com/bioinformatics/article/31/10/1671/176975)
- Ye, Congting; Ji, Guoli; **Li, Lei**; Liang, Chun;    *detectIR: a novel program for detecting perfect and imperfect inverted repeats using complex numbers and vector calculation*   **_PloS one_**  2014 [PLoS One](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0113349)
- Shi, Jieming; Dong, Min; **Li, Lei**; Liu, Lin; Luz-Madrigal, Agustin; Tsonis, Panagiotis A; Del Rio-Tsonis, Katia; Liang, Chun;  *mirPRo–a novel standalone program for differential expression and variation analysis of miRNAs*    **_Scientific reports_**    2015 [Scientific Reports](https://www.nature.com/articles/srep14617)



