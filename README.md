# E01 extension for OMOP CDM


# Purpose
add columns that store the origin of information (beyond type concepts)

# Added columns
`source_table_id` for id (typicaly table name) of the table where the data for the given OMOP row originate
`source_table_row_id` for row number in the source table where the data for the given OMOP row originate

