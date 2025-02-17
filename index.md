---
---

Data Carpentry aims to teach researchers basic concepts, skills, and tools 
for working
with data so they can get more done quickly and with less pain. This workshop uses 
Data Carpentry's approach to
teach data management and analysis for metagenomics research, including: 
best practices for the organization of bioinformatics projects and data, use
of command-line utilities, use of command-line tools to analyze sequence quality, 
use of R studio and use of R libraries to compare diversity between samples, 
and connecting to and using cloud computing. 
This workshop is designed to be taught over two full days of instruction.

Would you be interested in teaching these materials? We have an 
[Slack channel](https://join.slack.com/t/metagenomicslesson/shared_invite/zt-1tikq2o0k-VMX7ceLfenbbKheZ7XNCRw) 
were we will be happy to help you!


> ## Frequently Asked Questions
> Read our [FAQ](https://prodriguez19.github.io/metagenomics-workshop/faq/index.html) to learn more about Data Carpentry's Metagenomics workshop as an Instructor or a workshop host.
{: .callout}

> ## Getting Started
>
> This lesson assumes that learners have no prior experience with the tools covered in the workshop.   
> 
> However, learners are expected to have some familiarity with biological concepts,
> including the 
> concept of DNA sequencing, nucleotide abbreviations, genome, microbiome, and taxonomy. Participants should bring their own laptops and plan to participate actively.  
> 
> To get started, follow the directions in the [Setup](https://prodriguez19.github.io/metagenomics-workshop/setup.html) tab to 
> get access to the required software and data for this workshop.
> 
{: .prereq}

> ## Data
> 
> This workshop uses data from the environmental experiment: [Genomic adaptations in information 
> processing underpins trophic strategy in a whole-ecosystem nutrient 
> enrichment experiment](https://elifesciences.org/articles/49816), by Jordan G Okie et al.
> In this research, authors compared the differences between the microbial community 
> in its natural, oligotrophic, phosphorus-deficient 
>environment, a pond from the Cuatro Ciénegas Basin (CCB), and the same microbial 
>community under a fertilization treatment.
>
> All of the data used in this workshop can be downloaded from
> [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7010950.svg)](https://doi.org/10.5281/zenodo.7010950)
> More information about this data is available on the [Data page](https://prodriguez19.github.io/metagenomics-workshop/data/index.html).
{: .prereq} 

# Workshop Overview 

| Lesson    | Overview | Estimated time|
| ------- | ---------- | ---------- |
| [Project Organization and Management](https://prodriguez19.github.io/metagenomics-organization/) | Learn how to structure your metadata, organize and document your metagenomics data and bioinformatics workflow, and access data on the NCBI sequence read archive (SRA) database.|1:30 hr|  
| [Introduction to the Command Line](https://prodriguez19.github.io/metagenomics-shell/) |  Learn to navigate your file system, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards. | 4:00 hr| 
|[Introduction to R](https://prodriguez19.github.io/metagenomics-R/) | Use R studio to manage several data types and structures. | 1:00 hr| 
|[Data Processing and Visualization for Metagenomics](https://prodriguez19.github.io/metagenomics-analysis/) | Use command-line tools to perform quality control, metagenomic assembly, metagenomic binning, taxonomic assignment, and diversity exploration. | 6:30 hr| 

<!--
# Optional Additional Lessons

| Lesson | Overview |
| ------- | -------- |
| [16S genomics](https://datacarpentry.org/genomics-r-intro/) | Use R to analyze and visualize between-sample variation. |
!-->


## Citation
Please cite as:
[![DOI](https://jose.theoj.org/papers/10.21105/jose.00209/status.svg)](https://doi.org/10.21105/jose.00209)

Claudia Zirión Martínez; Diego Garfias Gallegos; Tania Vanessa Arellano Fernández; Aarón Espinosa Jaime; Edder D Bustos Díaz; José Abel Lovaco Flores; Luis Gerardo Tejero Gómez; J Abraham Avelar Rivas; Nelly Sélem (March , 2023) A Data Carpentry- Style Metagenomics Workshop

# Lessons Reference
The content of this page and three of the lessons presented in this workshop are adapted from lessons on the [Data Carpentry Genomics Workshop](https://datacarpentry.org/genomics-workshop/).
Lesson 1, Lesson 2, and Lesson 4, specifically Episode 2. Assessing Read Quality, and 3. Trimming and Filtering are adapted from the corresponding episodes in the [Data Wrangling and Processing for Genomics](https://datacarpentry.org/wrangling-genomics/) lesson that is Copyright (c) [The Carpentries](https://carpentries.org/). Materials licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) by the authors: Josh Herr, Ming Tang, Lex Nederbragt, Fotis Psomopoulos (eds): Version 2017.11.0, November 2017. THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
