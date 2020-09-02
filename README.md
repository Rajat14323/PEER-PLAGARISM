# PEER-PLAGARISM
This tool is basically made to detect the plagiarism amoung the documents.All you need to do is keep all the documents in the folder and it will give you the similarity score.

How It is different from simple comparision ???
If we compare every document with every other document then sometime it is not feasible as for large  data it may not be possible to load every documents in the ram at the same time and also its complexity will be O(n^2).
                           To overcome this problem Big Data Technology called Locality Sensisitive Hashing is used.In short it can be dercribe as a its maps the similar documents to same bucket using some hashing function and its compares only those documents which are mapped in the same bucket.                           
