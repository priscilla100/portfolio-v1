<div align="center">
	<h1>Blossom Academy Fall 2019 Cohort - Data Engineering</h1>
</div>

## Setup
<h1>Project One</h2>
I built a btasic ETL pipeline to read data from a source, transform this data, 
then load the output into a prescribed location.

Tools Used
- Pandas 
- Amazon Simple Storage Service(S3)

<h2>Task Performed</h2>

- Setup a working environment on computer to use throughout the program.
- Write a python script with the following features; 
    a. Download the 7+ Million Dataset from S3 [bucket: blossom-data-engs key:-project1/free-7-million-company-dataset.zip].
    b. Read the file with pandas.
    c. Filter out companies without a domain name using pandas.
    d. Write out the output(from point c.) in the following formats 
        * Parquet
        * JSON (compressed using gzip)
        * AVRO
- Upload the resulting 3 file to your S3 buckets blossom-data-eng-[student-name].
- Commit your code to your github repository.

