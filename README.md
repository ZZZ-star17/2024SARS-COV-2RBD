# 2024SARS-COV-2RBD
The 2024_output_data_lineage_part1 and _part2 files were originally belong to one big file, which is splitted into 2 files for upload to github due to upload file size limit. These two files contain parent-child dataset that we used for finetuning VirusT5 model.

The 2024_output_data_lineage_count contain statistic information about the parent-child dataset we used for finetuning VirusT5.

There is no refernce RBD sequence from Wuhan-2019 in parent-child dataset, it is possibly excluded during the data-preprocessing process. We are not sure if it is the reason behind why the finetuning failed.
