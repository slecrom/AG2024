# 4. Ressources
	
Cette section regroupe un ensemble de fichier ressources utiles pour le TP

--------------------------------------------------------------------------------
## Données brutes

### Genomic features

Pour ce TP nous utiliserons la version 6.54 du génome de *Drosophila melanogaster* dont les fichiers de séquence au format fasta sont accessibles sur le [site FTP de Flybase](https://ftp.flybase.net/genomes/Drosophila_melanogaster/dmel_r6.54_FB2023_05/fasta/).
La liste ci-dessous peut-être directement importée dans votre serveur Galaxy. 

```
https://ftp.flybase.net/genomes/Drosophila_melanogaster/dmel_r6.54_FB2023_05/fasta/dmel-all-chromosome-r6.54.fasta.gz	dmel-r6.54-fasta
https://ftp.flybase.net/genomes/Drosophila_melanogaster/dmel_r6.54_FB2023_05/fasta/dmel-all-miRNA-r6.54.fasta.gz	dmel-r6.54-miRNA
https://ftp.flybase.net/genomes/Drosophila_melanogaster/dmel_r6.54_FB2023_05/fasta/dmel-all-miscRNA-r6.54.fasta.gz	dmel-r6.54-miscRNA
https://ftp.flybase.net/genomes/Drosophila_melanogaster/dmel_r6.54_FB2023_05/fasta/dmel-all-tRNA-r6.54.fasta.gz	dmel-r6.54-tRNA
https://ftp.flybase.net/genomes/Drosophila_melanogaster/dmel_r6.54_FB2023_05/gtf/dmel-all-r6.54.gtf.gz	dmel-r6.54-gtf
```

Séquence du transgène PLacZ
```
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_GenomicFeatures/download?path=%2F&files=PLacZ.fasta	PLacZ
```

### Petits ARN

La liste ci-dessous peut-être directement importée dans votre serveur Galaxy. Attention à ne sélectionner uniquement que les lignes correspondant aux deux échantillons sur lesquels vous allez travailler et qui sont indiqués dans le [tableau partagé dans l'onglet "petits ARN"](https://docs.google.com/spreadsheets/d/1y-uBdR2TVZUIbNjM-RPxKXeMFn0OD8izTTmc3xnEFjE/edit#gid=243437883).

```
GLKD
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_smallRNAseqData/download?path=%2F&files=ALBA28.fastqsanger.gz	GLKD-ALBA28
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_smallRNAseqData/download?path=%2F&files=ALBA29.fastqsanger.gz	GLKD-ALBA29
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_smallRNAseqData/download?path=%2F&files=ALBA30.fastqsanger.gz	GLKD-ALBA30

WT
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_smallRNAseqData/download?path=%2F&files=ALBA25.fastqsanger.gz	WT-ALBA25
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_smallRNAseqData/download?path=%2F&files=ALBA26.fastqsanger.gz	WT-ALBA26
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_smallRNAseqData/download?path=%2F&files=ALBA27.fastqsanger.gz	WT-ALBA27
```

### ARN

La liste ci-dessous peut-être directement importée dans votre serveur Galaxy. Attention à ne sélectionner uniquement que les lignes correspondant aux deux échantillons sur lesquels vous allez travailler et qui sont indiqués dans le [tableau partagé dans l'onglet "ARN"](https://docs.google.com/spreadsheets/d/1y-uBdR2TVZUIbNjM-RPxKXeMFn0OD8izTTmc3xnEFjE/edit#gid=418538100).

```
GLKD
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_RNAseqData/download?path=%2F&files=ALBA1.fastqsanger.gz	GLKD-ALBA1
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_RNAseqData/download?path=%2F&files=ALBA2.fastqsanger.gz	GLKD-ALBA2
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_RNAseqData/download?path=%2F&files=ALBA3.fastqsanger.gz	GLKD-ALBA3

WT
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_RNAseqData/download?path=%2F&files=ALBA4.fastqsanger.gz	WT-ALBA4
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_RNAseqData/download?path=%2F&files=ALBA5.fastqsanger.gz	WT-ALBA5
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_RNAseqData/download?path=%2F&files=ALBA6.fastqsanger.gz	WT-ALBA6
```

--------------------------------------------------------------------------------
## Amorces de qPCR

Vous pouvez visualiser les amorces que vous avez utilisé lors de vos quantifications par qPCR dans IGV en téléchargeant le fichier [PCRprimers.gff](ressources/PCRprimers.gff).

--------------------------------------------------------------------------------
## ChIP-seq

L'occupation de H3K9me2, H3K9me3 et Rhino (Rhi) a été déterminée par immunoprécipitation de la chromatine suivie de séquençage (ChIP-seq) à partir d'ovaires WT et d'ovaires Kdm3 GLKD.
Les fichiers de couverture ci-dessous ont été obtenus à l'aide de l'outil [BamCompare](https://deeptools.readthedocs.io/en/develop/content/tools/bamCompare.html) (Deeptools Galaxy version 3.3.2.0.0)  avec une taille de bin de 100 pb et le calcul de la différence des lectures IP input en rpm.

```
H3K9me2
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_ChIPseq/download?path=%2F&files=ChIPseq_H3K9me2_Ctrl.bigwig
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_ChIPseq/download?path=%2F&files=ChIPseq_H3K9me2_Kdm3GLKD.bigwig
H3K9me3
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_ChIPseq/download?path=%2F&files=ChIPseq_H3K9me3_Ctrl.bigwig
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_ChIPseq/download?path=%2F&files=ChIPseq_H3K9me3_Kdm3GLKD.bigwig
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_ChIPseq/download?path=%2F&
Rhino
files=ChIPseq_Rhino_Ctrl.bigwig
https://psilo.sorbonne-universite.fr/index.php/s/Kdm3_ChIPseq/download?path=%2F&files=ChIPseq_Rhino_Kdm3GLKD.bigwig
```


--------------------------------------------------------------------------------
## Locus de piRNA

Séquences fasta des piRNA clusters et du transgene lacZ cible.

```
https://psilo.sorbonne-universite.fr/index.php/s/AG_Ressources/download?path=%2F&files=20A.fasta
https://psilo.sorbonne-universite.fr/index.php/s/AG_Ressources/download?path=%2F&files=38C_1.fasta
https://psilo.sorbonne-universite.fr/index.php/s/AG_Ressources/download?path=%2F&files=38C_2.fasta
https://psilo.sorbonne-universite.fr/index.php/s/AG_Ressources/download?path=%2F&files=38C_3.fasta
https://psilo.sorbonne-universite.fr/index.php/s/AG_Ressources/download?path=%2F&files=42AB.fasta
https://psilo.sorbonne-universite.fr/index.php/s/AG_Ressources/download?path=%2F&files=80F.fasta
https://psilo.sorbonne-universite.fr/index.php/s/AG_Ressources/download?path=%2F&files=flamenco.fasta 
https://psilo.sorbonne-universite.fr/index.php/s/AG_Ressources/download?path=%2F&files=PA92_TransgeneCible.fasta
```

Vous pouvez récupérer les coordonnées génomiques des piARN stockés sur la [piRNAdb](https://www.pirnadb.org/download/archive/gff_gtf) aux formats GTF et GFF.

