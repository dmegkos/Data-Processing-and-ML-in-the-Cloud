# Big Data - Data Processing and Machine Learning in the Cloud

This repository contains the work done for the INM432 Big Data coursework. The project mainly focuses on the parallelisation of tasks with Spark and also explores parallel training using TensorFlow.

## Project Overview

The coursework revolves around the following sections:

### Section 0: Environment Setup

This section is dedicated to setting up the necessary environment for the project.

### Section 1: Data Preprocessing

The project uses a public dataset, "Flowers", which comprises 3600 images classified into 5 categories. The preprocessing tasks were parallelised in Spark using Google Cloud (GC) Dataproc. 

### Section 2: Data Read Speed Measurement

This section involves measuring the speed of reading data in the cloud. Different configurations are parallelised and measured using Spark.

### Section 3: Use of Preprocessed Data

The preprocessed data is used in TensorFlow/Keras. The tasks were executed on the GC AI-Platform, and different parallelisation approaches for multiple GPUs were tested.

### Section 4: Theoretical Discussion

The final section involves theoretical discussion based on two academic papers.

## Implementation Details

The project was implemented using PySpark for data preprocessing and measurement tasks, and TensorFlow/Keras for machine learning tasks. Google Cloud Platform tools like Dataproc and AI-Platform were also utilised.

## Submission Details

The project is submitted as an .ipynb file, and there is also a report provided as a PDF document, both of which can be found in this repository. The PDF report includes screenshots from the Google Cloud web interface, result tables, as well as written text about the analysis.

## Notes

Performance of all operations were timed and performance information for cloud operations was obtained from the web interfaces for analysis and reporting.