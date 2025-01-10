# AutoClipper

Clip genes out of genomes and organize the results into a file system with the following structure:
dest_dir > gene_name > strain.fasta
Where strain.fasta contains all polymorphisms of a given gene for that strain.

This python notebook is written for maximum accessibility to new Python programmers.
Just follow the instructions I wrote in the code's comments and make the AutoClipper work for you!


This could be a helpful start to aalyze gene variation betwee strains.
Consider creating a pHMM or running multi-sequence alignment on the output .fasta files.
Additional tools like VirStrain would be helpful to classify isolates or samples to strains.
