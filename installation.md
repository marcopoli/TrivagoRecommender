install_requires =
numpy
pandas
click

### Baseline algorithm
To execute the code for the baseline algorithm, run::

    rec-popular --data-path=<path-to-csv-files-directory>


### Verify submission
To execute the code to verify the results format, run::

    verify-results --data-path=<path-to-csv-files-directory> --submission-file <name-of-submission-file> --test-file <name-of-provided-test-file>


### Score Results
To execute the code to score the results, run::

    score-results --data-path=<path-to-csv-files-directory> --submission-file <name-of-submission-file> --ground-truth-file <name-of-ground-truth-file>
