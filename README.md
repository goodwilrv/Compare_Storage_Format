#We know that parquet format is a columnar format of data storage which helps in compression and serialization of the objects while saving on the disk.

#In this Notebook: I am trying different formats of disk storage in python like .csv, .pickle, parquet, .feather etc and comparing the time it takes to read/write 1 million rows of a dataframe and it maintains the datatype after writting and reading back.

#Conslusion We see that for a 4.5 million rows dataframe parquet format takes 1/20th time (21.1 sec for .csv and 1.7 sec for parquet). Parquet format also take around 1/6th disk space compared to .csv format(238MB -> 48MB) approx.
