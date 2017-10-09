Welcome to the BPA-CSIRO workshops project on GitHub. 
This serves as a landing page for the various training workshops organised and maintained by BPA-CSIRO.
An overview of the training workshops and included training modules are described below. 
For the latest upcoming BPA-CSIRO workshops, please visit the Bioplatforms
Australia [training page][bpa-workshops].

## [Cancer Genomics][btp-workshop-cancer]
The Cancer Genomics workshop aims to provide an introduction to cancer genomics analytical pipelines 
for single nucleotide variations (SNV), copy number variations (CNV) and structural variations (SV).

| Training Modules                                   |
|:---------------------------------------------------|
| [Introduction to Command Line][btp-module-ngs-cli] |
| [Data Quality][btp-module-ngs-qc]                  |
| [Read Alignment][btp-module-ngs-mapping]           |
| [Single Nucleotide Variant Calling and Annotation][btp-module-cancer-snv]                 |
| [Copy Number Variation][btp-module-cancer-cnv]                   |
| [Structural Variant Analysisy][btp-module-cancer-sv]   |
| [Variant Visualisation][btp-module-cancer-viz]   |

## [Introduction to Next Generation Sequencing Hands-on Workshop][btp-workshop-ngs]

This is a practical 3 day hands-on course designed for bench biologists, 
PhD students or early career postdoctoral researchers with no or 
basic bioinformatics experience who are planning or currently using
NGS approaches in their research area. It will include a half-day
introduction to the command line interface. The training modules 
included in this workshop are listed below:

| Training Modules                                   |
|:---------------------------------------------------|
| [Introduction to Command Line][btp-module-ngs-cli] |
| [Data Quality][btp-module-ngs-qc]                  |
| [Read Alignment][btp-module-ngs-mapping]           |
| [ChIP-Seq][btp-module-ngs-chipseq]                 |
| [RNA-Seq][btp-module-ngs-rnaseq]                   |
| [de novo Genome Assembly][btp-module-ngs-denovo]   |

### Getting Started

The `Introduction to Next Generation Sequencing Hands-on Workshop` image can be 
launched on the NeCTAR Research Cloud and Amazon Web Services (AWS) cloud platforms.
A detailed guide on launching the image on the NeCTAR Research Cloud 
is available [here][btp-orch-nectar-launch]. 
The latest virtual machine on the NeCTAR Research Cloud is:

| Name             | ID                                     |
|:-----------------|:---------------------------------------|
| `BTP-2016-01-25` | `9c7fd8ac-5cfe-4067-aae3-82e53a49def3` |
 
A detailed guide for launching the image on AWS is also available [here][btp-orch-aws-launch]. 
On AWS, the latest virtual machine image (AMI) is available on the following regions:

| Region           | AMI            |
|:-----------------|:---------------|
| `ap-southeast-2` | `ami-be597ddd` |
| `eu-west-1`      | `ami-d3a31ea0` |

Stand-alone virtual machine images are also available for VirtualBox and VMWare.
These are downloadable from [here][bpa-ngs-releases]. Once downloaded,
it can be loaded straight into VirtualBox or VMWare.
VirtualBox or VMWare must be installed on the client machine.

The latest handouts for the `Introduction to Next Generation Sequencing Hands-on Workshop`
are available [here][bpa-ngs-handouts].

---

### Licence

All of these components, scripts and configuration tools make up the BTP and are managed and available on GitHub (https://github.com/BPA-CSIRO-Workshops) and are licensed under a Creative Commons Attribution 3.0 Unported License.

[btp-workshop-ngs]: https://github.com/BPA-CSIRO-Workshops/btp-workshop-ngs
[btp-module-ngs-cli]: https://github.com/BPA-CSIRO-Workshops/btp-module-ngs-cli
[btp-module-ngs-qc]: https://github.com/BPA-CSIRO-Workshops/btp-module-ngs-qc
[btp-module-ngs-mapping]: https://github.com/BPA-CSIRO-Workshops/btp-module-ngs-mapping
[btp-module-ngs-chipseq]: https://github.com/BPA-CSIRO-Workshops/btp-module-chip-seq
[btp-module-ngs-rnaseq]: https://github.com/BPA-CSIRO-Workshops/btp-module-rna-seq
[btp-module-ngs-denovo]: https://github.com/BPA-CSIRO-Workshops/btp-module-velvet
[btp-module-cancer-snv]: https://github.com/BPA-CSIRO-Workshops/cancer-module-snv
[btp-module-cancer-cnv]: https://github.com/BPA-CSIRO-Workshops/cancer-module-cnv
[btp-module-cancer-sv]: https://github.com/BPA-CSIRO-Workshops/cancer-module-sv
[btp-module-cancer-viz]: https://github.com/BPA-CSIRO-Workshops/cancer-module-viz
[btp-workshop-template]: https://github.com/BPA-CSIRO-Workshops/btp-workshop-template#minting-a-doi-for-your-workshop
[btp-orchestration]: https://github.com/BPA-CSIRO-Workshops/btp-orchestration
[btp-orch-nectar-launch]: https://github.com/BPA-CSIRO-Workshops/btp-orchestration#nectar-1
[btp-orch-aws-launch]: https://github.com/BPA-CSIRO-Workshops/btp-orchestration#aws-1
[bpa-workshops]: http://www.bioplatforms.com/training/
[bpa-ngs-releases]: https://github.com/BPA-CSIRO-Workshops/btp-workshop-ngs/releases
[bpa-ngs-handouts]: http://bpa-csiro-workshops.github.io/btp-workshop-ngs/
