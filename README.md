# gatk_tools
GATK and other bioinformatics tools packaged together.

If you make use of this image, please acknowledge 
Sydney Informatics Hub at the University of Sydney https://informatics.sydney.edu.au/

#Build with:
```sudo docker build . -t gatk```

#Run with something like:
```sudo docker run --rm -it -v `pwd`:/workspace gatk```
Or on Windows
```docker run --rm -it -v C:\WORK\ShortProjects\GATK:/workspace gatk ```


## Java 
openjdk version "1.8.0_191"
OpenJDK Runtime Environment (build 1.8.0_191-8u191-b12-0ubuntu0.16.04.1-b12)
OpenJDK 64-Bit Server VM (build 25.191-b12, mixed mode)  

https://openjdk.java.net/

## GATK
The Genome Analysis Toolkit (GATK) v4.1.2.0
HTSJDK Version: 2.19.0 
Picard Version: 2.19.0

https://software.broadinstitute.org/gatk/download/

## Samtools
Version: 0.1.19-96b5f2294a

http://www.htslib.org/

## fastp
fastp 0.20.0 

https://github.com/OpenGene/fastp

## BWA
Version: 0.7.15-r1140 

http://bio-bwa.sourceforge.net/
https://github.com/lh3/bwa

## Sambamba
sambamba 0.7.0 
LDC 1.10.0 / DMD v2.080.1 / LLVM6.0.1 / bootstrap LDC - the LLVM D compiler (0.17.4)

https://lomereiter.github.io/sambamba/
