###############################
# DBLINK-DDBJ Tables 
# Table names, description and examples
# Part of DBLINK-DDBJ database, developed and designed by Andrea Ghelfi 
###############################

directory structure
/home/w3const/dblink-ddbj/dblink_ddbj_standby
./gea/gea_dblink.csv
./tsunami/bp_actual_taxon.csv
./tsunami/biosample_actual.csv
./tsunami/drr_actual.csv
./tsunami/table_accession_type.csv
./tsunami/table_accession_current2obsolete.csv
./trace/dblink_trace_bs_table.csv
./trace/dblink_trace_bp_table.csv
./trace/dblink_trace_drr_table_status.csv

The /home/w3const/dblink-ddbj/tables has the same .csv files shown above.

------------------
gea	
------------------
File name
gea_dblink.csv

Description
gea ID, status, bioproject

Example
E-GEAD-295,300,PRJDB7316
------------------
tsunami
------------------
File name
bp_actual_taxon.csv

Description
db_name, accession, bioproject, taxon, status, accept_date, count	

Example
e-actual,IAAH01,PRJDB3798,1635099,1002,2016-02-29,17854
---
File name
biosample_actual.csv
	
Description
accession, biosample
	
Example
ICSQ01,SAMD00519231
---
File name
drr_actual.csv
	
Description
accession, drr
	
Example
IAAD01,DRR048569
---
File name
table_accession_type.csv

Description
accession, type (primary/secondary)
DB636774,pri

Example
DB678285,sec
---
File name
table_accession_current2obsolete.csv
	
Description
accession (current), accession2 (obsolete)
	
Example
DB636774,DB678285
------------------
trace
------------------
File name
dblink_trace_bs_table.csv
	
Description
biosample ID, submitter, submission ID, status, taxon, locus_tag, bioproject
	
Example
SAMD00000510,hajime_takahashi,SSUB000079,5500,1639,LmNIHS28,PRJDB1730
---
File name
dblink_trace_bp_table.csv
	
Description
submitter, submission ID, status, project_type, locus_tag, bioproject
	
Example
hajime_takahashi,PSUB002175,5500,primary,IGM28,PRJDB1730
---
File name
dblink_trace_drr_table_status.csv
	
Description
drr, bioproject, biosample, submitter, status
	
Example
DRR523864,PRJDB17303,SAMD00729823,hkondo,700
