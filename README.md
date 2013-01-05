# Testing links to other files in Github repo

```R
setwd("sample_files/output/")
expt.name <- "demo"
file.name <- "log_barcodes_observed.fq_sequences.bar_barcode.list.tsv"
barcode_plot(file.name, expt.name)
```

<!--
    # The above snippet is the Github syntax-highlighted version of this:
    setwd("sample_files/output/")
    expt.name <- "demo"
    file.name <- "log_barcodes_observed.fq_sequences.bar_barcode.list.tsv"
    barcode_plot(file.name, expt.name)
 -->

```bash
./barcode_split_trim.pl \
  --barcode sample_files/barcode.list \
  --list \
  --outdir sample_files/output \
  sample_files/sequences.fq
```

<!--
    # The above snippet is the Github syntax-highlighted version of this:
    ./barcode_split_trim.pl \
      --barcode sample_files/barcode.list \
      --list \
      --outdir sample_files/output \
      sample_files/sequences.fq
 -->

    ./barcode_split_trim.pl \
      --barcode sample_files/barcode.list \
      --list \
      --outdir sample_files/output \
      sample_files/sequences.fq


[file_a](file://folder_1/linked_file_a)

[file_a absolute link](https://github.com/mfcovington/link_test/blob/master/folder_1/linked_file_a)

[file_a absolute link - raw path](https://raw.github.com/mfcovington/link_test/master/folder_1/linked_file_a)

[link to image](https://github.com/mfcovington/link_test/blob/master/folder_1/demo.barcodes.png)

![image](https://github.com/mfcovington/link_test/blob/master/folder_1/demo.barcodes.png)

![image - raw path](https://raw.github.com/mfcovington/link_test/master/folder_1/demo.barcodes.png)

[link to folder](https://github.com/mfcovington/link_test/blob/master/folder_1/)

<img src="https://raw.github.com/mfcovington/link_test/master/folder_1/demo.barcodes.png" height="300" />

<img src="https://raw.github.com/mfcovington/link_test/master/folder_1/demo.barcodes.png" height="500" />

<img src="https://raw.github.com/mfcovington/link_test/master/folder_1/demo.barcodes.png" height="700" />

<img src="https://raw.github.com/mfcovington/link_test/master/folder_1/demo.barcodes.png" height="900" />

