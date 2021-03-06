# SARS-CoV-2 Mutations of Interest

<sub>Created and maintained by Dr Emma B Hodcroft, University of Bern. Please credit and link back to this site if you use this resource!</sub>

_*This page is under construction & more on the missing variants will be added soon.*_

These collection of Github pages is intended to provide an overview (not necessarily  complete) of SARS-CoV-2 mutations that are of interest.
It should be noted that these mutations are primarily of interest due to spread in Europe: this is simply a reflection that the primary maintainer/author (Emma Hodcroft) works mostly with European data.
<!-- I support and urge others to set up similar sites for non-European clusters/mutations - I will happily link them here if you get in touch. -->

The code used to generate these tables, graphs, and the sequences related to that mutation can be found in this repository.

**The SARS-CoV-2 pandemic & research surrounding it is ongoing.**
I will make every effort to try to keep this repository up-to-date, but readers should take care to double-check that the information is the latest available. <br>
**I welcome PR requests to this repository providing new links and information!**
The more detail you can include in a pull request (PR) the faster I'll be able to review it.
If possible, provide a PR that adds/edits the appropriate links/etc, and I can merge it faster - if you can't do that, making an [issue](https://github.com/emmahodcroft/cluster_scripts/issues) is fine, but I might be slower incorporating it.


_*Where is the 69/70 deletion section?*_<br>
This deletion has arisen at least 3 times independently: in the `S:Y453F`, `S:N439K`, and `S:N501Y` clusters.
There's also a recent preprint which suggests it may alter the recognition by antibodies, possibly impacting some antibody-therapy treatments, or immunity ([Kemp et al. medRxiv](https://www.medrxiv.org/content/10.1101/2020.12.05.20241927v1)).
So, there's a lot of interest in this variant. <br>
For boring, technical, code reasons I do not yet have a dedicated 69/70 deletion build, but I'm working on it!


## Mutations

[Overview of all mutation tables & graphs](table_overview.md)

[Overview of all mutation country plots](country_overview.md)

### Index
Clusters/mutations are listed below by the location of a mutation in the spike protein (`S:`) - the letter after `:` indicates the original amino-acid, the number the position in the spike protein, and the last letter, the 'new' amino-acid.<br>
As `S:N501` has multiple amino-acid mutations, there is no second letter.<br>
20A.EU1 and 20A.EU2, because of their prominence, have been given 'subclade' names.
The mutation is listed in parentheses after the name.

- [20A.EU1](#20aeu1) _(S:A222V)_
- [20A.EU2](#20aeu2) _(S:S477N)_
- [S:S98F](#ss98f)
- [S:D80Y](#sd80y)
- [S:N439K](#sn439k)
- [S:Y453F](#sy453f)
- [S:N501](#sn501)
- [S:A626S](#sa626s)
- [S:V1122L](#sv1122l)
- [S:H69-](#sh69-)

## 20A.EU1  _(S:A222V)_
![Figure of S:A222V](/other_figures/222.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub>

[Dedicated 20A.EU1 Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/20A.EU1?f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/20A.EU1_table.md)

- Defining mutations:
  - Nonsynonymous: `S:A222V`; `ORF10:V30L`; `N:A220V` or `ORF14:L67F` (overlapping reading frame with `N`)
  - Synonymous: `T445C`, `C6286T`, `C26801G`
- `S:A222V`
  - Mutation in the non-terminal domain (NTD), which is not known to play a direct role in receptor binding or membrane fusion
  - Associated with a cluster that initially expanded in Spain and spread across Europe via holiday travel ([see Hodcroft et al preprint](https://www.medrxiv.org/content/10.1101/2020.10.25.20219063v2))

## 20A.EU2  _(S:S477N)_
![Figure of S:S477N](/other_figures/477.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub>

[Dedicated 20A.EU2 Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/20A.EU2?f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/20A.EU2_table.md)

- _Note this cluster is only the European appearance of S:477N_
- Defining mutations:
  - Nonsynonymous: `S:S477N`; `N:M234I`, `A376T`; `ORF1b:A176S`, `V767L`, `K1141R`, `E1184D`
  - Synonymous: `C4543T`, `G5629T`, `C11497T`, `T26876C`
- `S:S477N`
  - Mutation is in the receptor binding domain (RDB), important to ACE2 binding and antibody recognition
  - Has arisen independently in Australia and was responsible for much of the summer 2020 outbreak ([Link to Nextstrain build](https://nextstrain.org/ncov/oceania/2020-11-16?c=gt-S_477))
  - May slightly increase ACE2 binding: [Chen et al. JMB](https://www.sciencedirect.com/science/article/pii/S0022283620304563); see also [Bloom Lab ACE2 binding website](https://jbloomlab.github.io/SARS-CoV-2-RBD_DMS/)
  - May confer resistance to antibodies: [Gaebler et al. bioRxiv](https://www.biorxiv.org/content/10.1101/2020.11.03.367391v1)

## S:N439K
![Figure of S:N439K](/other_figures/439.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub>

[Dedicated S:N439K Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/S.N439K?c=gt-S_439&f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/S.N439K_table.md)

- Defining mutations:
  - Nonsynonymous: `S:N439K`; `ORF1a:I2501T`
  - Synonymous: `C8047T`
- `S:N439K`
  - Mutation is in the receptor binding domain (RDB), important to ACE2 binding and antibody recognition
  - About 2/3 of the sequences in the cluster have deletions at Spike amino-acid positions 69/70 ([Nextstrain build with deletions in cluster highlighted](https://nextstrain.org/groups/neherlab/ncov/S.N439K?c=gt-S_69&label=clade:S.N439K))
  - Has emerged twice independently in Europe, but was exclusive to Scotland in the first wave and went extinct: [Thompson et al. bioRxiv](https://www.biorxiv.org/content/10.1101/2020.11.04.355842v1)
  - May increase ACE2 binding: [Thompson et al. bioRxiv](https://www.biorxiv.org/content/10.1101/2020.11.04.355842v1); see also [Bloom Lab ACE2 binding website](https://jbloomlab.github.io/SARS-CoV-2-RBD_DMS/)
  - Confers resistance to one of the two antibodies in the Regeneron cocktail (REGN10987); see [Starr et al. bioRxiv](https://www.biorxiv.org/content/10.1101/2020.11.30.405472v1.full) and [Thompson et al. bioRxiv](https://www.biorxiv.org/content/10.1101/2020.11.04.355842v1).
  - May confer resistance to antibodies: C135 ([Weisblum et al. eLife](https://elifesciences.org/articles/61312), [Barnes et al. Nature](https://www.nature.com/articles/s41586-020-2852-1)); a panel of antibodies ([Thompson et al. bioRxiv](https://www.biorxiv.org/content/10.1101/2020.11.04.355842v1))


## S:Y453F
![Figure of S:Y453F](/other_figures/453.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub>

[Dedicated S:Y453F Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/S.Y453F?c=gt-S_453&f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/S.Y453F_table.md)

- Defining mutations:
  - Has appeared multiple times independently: each can be associated with different accompanying mutations
- `S:Y453F`
  - Mutation is in the receptor binding domain (RDB), important to ACE2 binding and antibody recognition
  - Associated with the 'cluster 5' 'mink' variant that led to some alarm in Denmark in autumn 2020
    - This variant has the following additional spike mutations: 60/70 deletion, `I692V` and `M1229I`
  - It is has also been seen previously in mink in the Netherlands ([example Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/netherlands?c=gt-S_453&f_country=Netherlands&f_host=Mink))
  - May be a mink-specific adaptation, increasing binding to mink ACE2: ([Rodrigues et al. PloS Comp Bio](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008449)); and appearing multiple times ([van Dorp et al. bioRxiv](https://www.biorxiv.org/content/10.1101/2020.11.16.384743v1))
  - May also increase ACE2 binding in humans: [Bloom Lab ACE2 binding website](https://jbloomlab.github.io/SARS-CoV-2-RBD_DMS/)
  - Does confer resistance to an antibody in the Regeneron cocktail: REGN10933 ([Baum et al. Science](https://science.sciencemag.org/content/369/6506/1014/tab-pdf); [Starr et al. bioRxiv](https://www.biorxiv.org/content/10.1101/2020.11.30.405472v1.full))

## S:S98F
![Figure of S:S98F](/other_figures/98.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub>

[Dedicated S:S98F Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/S.S98F?c=gt-S_98&f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/S.S98F_table.md)

- Defining mutations:
  - Nonsynonymous: `S:S98F`; `N:P199L` or `ORF14:Q46*` (overlapping reading frames); `ORF3a:Q38R`, `G172R`, `V202L`
  - Synonymous: C28651T
- `S:S98F`
  - Mostly found in Belgium and the Netherlands - predominantly Belgium

_More coming soon_

## S:D80Y
![Figure of S:S98F](/other_figures/80.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub>

[Dedicated S:D80Y Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/S.D80Y?f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/S.D80Y_table.md)

_More coming soon_

## S:N501
![Figure of S:N501](/other_figures/501.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub>

[Dedicated S:N501 Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/S.N501?c=gt-S_501&f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/S.N501_table.md)

- Defining mutations:
  - Has appeared multiple times independently: each can be associated with different accompanying mutations
  - Amino-acid changes are `N501Y` (nucleotide mutation `A23063T`), `N501T` (nucleotide mutation `A23064C`), and `N501S` (nucleotide mutation `A23064G`)
- `S:N501`
  - Mutation is in the receptor binding domain (RDB), important to ACE2 binding and antibody recognition
  - Associated with a recently reported 'new variant' announced in the South East of England on 14 Dec 2020 ([COG-UK Report](https://www.cogconsortium.uk/news_item/update-on-new-sars-cov-2-variant-and-how-cog-uk-tracks-emerging-mutations/))
    - This particular variant is associated with multiple mutations in Spike, including: `N501Y`, a deletion at 69/70 (as seen in `S:N439K` & `S:Y453F`), and `P681H`
  - Clusters also seen in USA, South Africa, & Australia
  - May be associated with adaptation to rodents and mustelids: `N501T` in ferrets ([Richard et al. Nature Comm.](https://www.nature.com/articles/s41467-020-17367-2)); `N501Y` in mice ([Gu et al. Science](https://science.sciencemag.org/content/369/6511/1603))
    - Some have speculated of risk of a persistent reservoir in wild rodents/mustelids
  - May increase ACE2 binding: [Bloom Lab ACE2 binding website](https://jbloomlab.github.io/SARS-CoV-2-RBD_DMS/)
  - `N501Y` was found in longitudinally-collected samples from an immunocompromised patient ([Choi et al. NEJM](https://www.nejm.org/doi/full/10.1056/NEJMc2031364?query=featured_coronavirus))


## S:A626S
![Figure of S:A626S](/other_figures/626.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub>

[Dedicated S:A626S Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/S.A626S?f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/S.A626S_table.md)

_More coming soon_


## S:V1122L
![Figure of S:V1122L](/other_figures/1122.gif)

<sub>Figure made via [GISAID](https://gisaid.org)</sub> 

[Dedicated S:V1122L Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/S.V1122L?c=gt-S_1122&f_region=Europe)

[Table and charts of mutation distribution](cluster_tables/S.V1122L_table.md)

_More coming soon_

## S:H69-
![Figure of S:H69-](/other_figures/6970del.gif)

<sub>Figure made via [GISAID](https://gisaid.org)<br>
Note this figure shows both the 69 & 70 deletion.</sub>

[Dedicated S:H69- Nextstrain build](https://nextstrain.org/groups/neherlab/ncov/S.H69-?c=gt-S_69,501,453)

[Table and charts of mutation distribution](cluster_tables/S.H69-_table.md)

**Important**: *Currently this build detects only the deletion at position 69 in spike, as due to alignment/calling differences, detecting the deletion at position 70 is less reliable.*
*However, they seem to be highly associated.*

_More coming soon_
