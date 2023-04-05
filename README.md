# hse23_hw3

[Колаб](https://colab.research.google.com/drive/1a3rUgN-nCM939K53j2U7nAgyO17WZipN?usp=sharing)

### Метки Гистонов
Я выбрал клеточную линию HUVEC
Название | Файл
-- | --
H3K27ac | wgEncodeBroadHistoneHuvecH3k27acStdAlnRep1.bam
H3K27me3 | wgEncodeBroadHistoneHuvecH3k27me3StdAlnRep1.bam
H3K36me3 | wgEncodeBroadHistoneHuvecH3k36me3StdAlnRep1.bam
H3K4me1 | wgEncodeBroadHistoneHuvecH3k4me1StdAlnRep1.bam
H3K4me2 | wgEncodeBroadHistoneHuvecH3k4me2StdAlnRep1.bam
H3K4me3 | wgEncodeBroadHistoneHuvecH3k4me2StdAlnRep1.bam
H3K79me2 | wgEncodeBroadHistoneHuvecH3k79me2AlnRep1.bam
H3K9ac | wgEncodeBroadHistoneHuvecH3k9acStdAlnRep1.bam
H3K9me1 | wgEncodeBroadHistoneHuvecH3k9me1StdAlnRep1.bam
H4K20me1 | wgEncodeBroadHistoneHuvecH4k20me1StdAlnRep1.bam

### Содержание cellmarkfiletable.txt

Клеточная линия | Метка гистона | Файл с меткой | Контроль
-- | -- | -- | --
HUVEC |	H3K36me3 |	H3K36me3.bam | Control.bam
HUVEC	| H4K20me1 | H4K20me1.bam	| Control.bam
HUVEC	| H3K9ac | H3K9ac.bam | Control.bam
HUVEC	| H3K27ac	| H3K27ac.bam |	Control.bam
HUVEC	| H3K27me3 | H3K27me3.bam | Control.bam
HUVEC	| H3K4me2 | H3K4me2.bam	| Control.bam
HUVEC	| H3K4me3	| H3K4me3.bam	 | Control.bam
HUVEC	| H3K79me2 | H3K79me2.bam	| Control.bam
HUVEC	| H3K4me1	| H3K4me1.bam	| Control.bam
HUVEC	| H3K9me1	| H3K9me1.bam	| Control.bam

### ChromHMM
Emission

![Image](/data/emissions_15.png) 

Overlap

![Image](/data/HUVEC_15_overlap.png)

Transitions

![Image](/data/transitions_15.png)

RefSeqTTS

![Image](/data/HUVEC_15_RefSeqTSS_neighborhood.png)

RefSeqTes

![Image](/data/HUVEC_15_RefSeqTES_neighborhood.png)

### Эпигенетические типы

№ | Название | Метки | Скриншот
-- | -- | -- | --
1 | Repressed | Нет | ![Image](/states_sh/state_1.png)
2 | Heterochromatin | H3K27me3 | ![Image](/states_sh/state_2.png)
3 | Weak enhancer | H3K4me1, H3K4me2, H3K4me3, H3K9ac, H3K27me1 | ![Image](/states_sh/state_3.png)
4 | Strong enhancer | H3K4me1, H3K4me2, H3K4me3, H3K9ac, H3K27me1, H3K79me2 | ![Image](/states_sh/state_4.png)
5 | Inactive Promoter | H3K4me1, H3K4me2, H3K4me3, H3K9ac, H3K27me1, H3K79me2 | ![Image](/states_sh/state_5.png)
6 | Weak enhancer | H3K4me1, H3K4me2, H3K4me3, H3K27me1, H3K36me3, H3K79me2, H4K20me1 | ![Image](/states_sh/state_6.png)
7 | Weak enhancer | H3K4me1, H3K4me2, H3K4me3, H3K9ac | ![Image](/states_sh/state_7.png)
8 | Active Promoter | H3K4me1, H3K4me2, H3K27ac| ![Image](/states_sh/state_8.png)
9 |  Weak enhancer | H3K4me1, H3K4me2, H3K27ac | ![Image](/states_sh/state_9.png)
10 | Active Promoter | H3K4me1 | ![Image](/states_sh/state_10.png)
11 | Weak enhancer | H3K4me1, H3K4me2, H3K27ac, H3K79me2 | ![Image](/states_sh/state_11.png)
12 | Heterochromatin | H3K79me2 | ![Image](/states_sh/state_12.png)
13 | Weak transcribed | H3K36me3, H3K79me2 | ![Image](/states_sh/state_13.png)
14 | Heterochromatin | H3K36me3 | ![Image](/states_sh/state_14.png)
15 | Weak transcribed | H3K36me3, H4K20me1 | ![Image](/states_sh/state_15.png)




