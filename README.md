# Mountford
# Language: R
# Input: CSV (abundances)
# Output: CSV (dissimilarities)
# Tested with: PluMA 1.1, R 4.0.0
# Dependency: vegan_2.5.6

PluMA plugin that computes dissimlarity between community samples using the Mountford Dissimilarity Index (Mountford, 1962).
The plugin accepts input in CSV format with rows representing samples and columns representing community members.
Entry (i, j) then holds the abundance of community member j in sample i.

The plugin outputs a CSV file of dissimilarities, with both rows and columns corresponding to samples and entry (i, j)
holding the dissimilarity level between sample i and sample j.
