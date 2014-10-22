GirlyGenomes
============


Looking for genes from the CBF families 

We have found and chosen 4 representatives from A.thaliana and 4 representatives from O.sativa:

A.thaliana:

CBF4 - Q9FJ93 - http://www.uniprot.org/uniprot/Q9FJ93
CBF2 - Q9SYS6 - http://www.uniprot.org/uniprot/Q9SYS6
CBF1 - P93835 - http://www.uniprot.org/uniprot/P93835
CBF3 - Q9M0L0 - http://www.uniprot.org/uniprot/Q9M0L0

O. sativa: 

CBF3 - Q64MA1 - http://www.uniprot.org/uniprot/Q64MA1
CBF2 - Q8S9Z5 - http://www.uniprot.org/uniprot/Q8S9Z5
CBF1 - Q9LWV3 - http://www.uniprot.org/uniprot/Q9LWV3
CBF4 - Q9FJ93 - http://www.uniprot.org/uniprot/Q9FJ93

Changing headers of proteins from comp_transcript_database:

> sed 's/asmbl/Laura/g' Laura_comp | sed 's/|/_/g' | sed 's/ORF.*//' > Laura_comp_headers

cat Laura_comp_headers Lemtal_comp_headers Nerissa_comp_headers Temul_comp_headers /data/storage-02/ADRIAN_ANN/Perenne_input.fasta > Combined_compr_db.fasta
