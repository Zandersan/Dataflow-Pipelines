# Apache Beam - Dataflow Pipeline

Technology used: *Python, Apache Beam, GCP, Google Cloud SDK Shell*

## Abstract

This project was completed as part of a coding challenge. The goal was to perform data transformations on a public dataset about London bicycles to gather insights into London cycling behavior. The main task was to count the number of rides from one station to another and present the results in a text file in the following format: (start_id, end_id, number_of_rides).

## Process

1. Set up the GCP project and authenticated with Google Cloud SDK.
2. Created an S3 bucket with the input data and Python script.
3. Prepared the rides_counter.py script and built the pipeline using apache_beam.
4. Ran the script to initialize the Dataflow pipeline.
5. Reviewed the data.

## Source code: Python script & pipeline dependencies

[*rides_counter.py*](https://github.com/Zandersan/Dataflow-Pipelines/blob/main/rides_counter.py)

[*setup.py*](https://github.com/Zandersan/Dataflow-Pipelines/blob/main/setup.py)

## Output

The outcome was a [*outfile.txt*](https://github.com/Zandersan/Dataflow-Pipelines/blob/main/output.txt) file that presents results in expected format.
