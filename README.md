# htseq-count
htseq-count test data for issue:

https://github.com/htseq/htseq/issues/54

Different versions of HTSeq were tested and newer versions (1.99.2 and newer) the counts differ with older version (0.13.5 and older)

singularity run -B /mnt /mnt/shared/development/htseq-1.99.2.sif htseq-count -s yes subset.sam subset.gtf >counts_1.99.2.raw
