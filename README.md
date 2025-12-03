# Excel-XLOOKUP

VLOOKUP:
Looks for a value in the first column of a table and returns a value in the same row from a specified column.
Formula: 
=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])


INDEX & MATCH:
Combines two functions: MATCH finds the row or column number of a value, and INDEX returns the value at a given position within a range.
Formula:
=INDEX(return_array, MATCH(lookup_value, lookup_array, [match_type]))

XLOOKUP:
Replaces VLOOKUP, INDEX, and MATCH by combining their best features into a single, more powerful and user-friendly function.
Formula:
=XLOOKUP(lookup_value, lookup_array, return_array, [if_not_found], [match_mode], [search_mode])
