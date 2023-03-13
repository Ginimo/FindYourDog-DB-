# Find your dog

## SUMMARY

Dogs are just as different as people. There are breeds that have been bred especially for hunting. Others are very sporty or are well suited as guard dogs or for searching. Still others are particularly comfortable and like it best at home on the couch.
To make people and dogs happy, I came up with the idea of making a database available. With this database, different people should use aggregation pipelines within the Mongo DB to find a dog that best fits the person's circumstances, needs and preferences

The ELT pipeline is based on a mixture of Python and NoSQL.

This project was conducted by Daniel Podolecki.

## DATA

The data is extracted from two different APIs the Dog API and the Dog Breed API. For that you will need to configure your own API Keys.

## USAGE 

To run this project a Mongo DB has to be configured and the connection setup in the chapter 3 Requirements & Configuration has to be adapted accordingly to your own MongoDB.
In particular, the CNX_String must be replaced as defined in the script.

The analysis requires the user to have Jupyter Notebook installed on his / her computer. Another option is to open the .ipynb file on Google Colab, where you can insert all the data and then refer to the storage-folder, which is the recommended approach since the autohors created the report with the use of Google Colab.
