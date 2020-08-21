# Somatic variant calling tutorial using GATK 

Using the pipeline instruction from the official [GATK page](https://gatk.broadinstitute.org/hc/en-us/articles/360035894731-Somatic-short-variant-discovery-SNVs-Indels-)
this is a tutorial on how to do somatic variant calling. There is also a user [issue](https://gatk.broadinstitute.org/hc/en-us/community/posts/360056100851-Somatic-pipeline-from-FASTQ-to-VCF) that help
explain partially some of the ways to use `MuTech2` to do somatic variant calling. More issues include [this one](https://gatk.broadinstitute.org/hc/en-us/community/posts/360057810051-Mutect2-somatic-variant-calling-with-without-matched-normal-sample) and [this one](https://gatk.broadinstitute.org/hc/en-us/community/posts/360061543792-Panel-of-Normals-Documentation).  

This [article](https://gatk.broadinstitute.org/hc/en-us/articles/360035890491-Somatic-calling-is-NOT-simply-a-difference-between-two-callsets) explains more details on somatic variant calling. 

Data can be obtained from the 1kGP sample [HG00265](https://www.internationalgenome.org/data-portal/sample/HG00265).  

This [bucket](https://console.cloud.google.com/storage/browser/gatk-best-practices/somatic-hg38?prefix=) from GATK contains multiple useful files such as PoNs from 1kGP and the germline-resource from gnomad 
