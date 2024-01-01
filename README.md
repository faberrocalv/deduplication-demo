# Deduplication demo

Simple implementation of a duplicate detection technique, an alternative to fuzzy comparison of strings, using the `dedupe` python library which applies a live labeling process of possible duplicate records to subsequently train a classification model to identify the remaining duplicate records in the entire dataset.

- `dedupe_csv_quick_demo.ipynb`: A notebook with a simple example of the implementation of the library using data from [2].
- `csv_example.py`: A python executable (inside dedupe_docs_example folder) with an example extracted from [3].

## References:

- **[1]:** https://docs.dedupe.io/en/latest/index.html
- **[2]:** https://github.com/vintasoftware/deduplication-slides/blob/master/slides.ipynb
- **[3]:** https://github.com/dedupeio/dedupe-examples/tree/master/csv_example
