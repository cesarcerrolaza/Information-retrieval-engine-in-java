# Information-retrieval-engine-in-java
A multiple file indexer and information retrieval engine programmed in java.
This is a Spanish user version, this can be changed by rewriting the System.out.println()

Before the execution it is needed to create a directory called "corpus" in the proyect directory with the files you need to index, also you'll have to change the string that contains the corpus Path and add your own Path in UserApp.java (line 15).
When the proyect is executed, two options will apear: first one is to create the index of the corpus and file largeness vector, that will be saved Indice.txt and Longitud.txt, the second option will let you introduce your query and will use the Indice.txt and Longitud.txt to make the files ranking using the vector space model
