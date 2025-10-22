File loaded and initial row/column counts (2240 rows × 29 columns)

Columns renamed to lowercase and underscores.

Date columns converted to datetime and formatted to dd-mm-yyyy; printed newest/oldest using .strftime('%d-%m-%Y').

Missing values: which columns had missing values and how they were handled (filled with median/mode/unknown, or rows removed).

Duplicates: number of duplicates removed and method used.

Text normalization: e.g., gender standardized to male/female/unknown.

Data types corrected (list specific columns that changed type).

Any outliers capped or removed (if done).

Derived columns added (if any).

Final row/column counts and file exported as cleaned_dataset.csv (or .xlsx).
