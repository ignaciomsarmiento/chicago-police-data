# -*- coding: utf-8 -*-

# Authors:	Roman Rivera (Invisible Institute)
# individual/TRR-charges_2004-2016_2016-09_p046360/import/src/Makefile

.PHONY: all clean
# Additional files created: import.log, import.yaml,
# metadata_TRR-charges_2004-2016_2016-09.csv.gz

all: \
		output/TRR-charges_2004-2016_2016-09.csv.gz

output/TRR-charges_2004-2016_2016-09.csv.gz: \
		src/import.py \
                input/10655-FOIA-P046360-TRRdata_sterilized.xlsx
	python $<


clean:
	rm output/*


# done
