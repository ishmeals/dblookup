One thing that caught me off guard is that it will be installed in '/usr/local/helib_pack'.
To get it to install in '/usr/local', set `PACKAGE_DIR=/usr/local`

# Country Lookup Example
This example demonstrates a privacy preserving search against an encrypted 
database and it is implemented using the [Brakerski-Gentry-Vaikuntanathan][1] 
(BGV) scheme. The database is a key-value store pre-populated with the 
English names of countries and their capital cities from the continent of 
Europe. Selecting the country will use HElib to perform a search of the 
matching capital.

## Relation to a real use case
Privacy preserving search is a common scenario to demonstrate the benefits of
homomorphic encryption. Being able to perform a query while preserving the
privacy and confidentiality of the parameters of the query has many
applications across various industry segments spanning from genomics to
finance. This example uses a simple and easy to follow algorithm that
demonstrates how one can use homomorphic encryption based techniques to
generate a mask to retrieve data from a key-value pair database. It uses a
dataset that is understandable for users across all industries and expertise
levels. 

With respect to realism of data, the dataset takes into account all countries
in the continent of Europe. In a real use case, this could be information on
customers or financial records for example. This is an educational example so a
small dataset was needed to ensure timely responses and that it was relevant
for all users.


