Wasp:megastore-like system.
====
In recent years, along with the rise of Bigtable and NoSQL, Community products HBase gradually toward the NoSQL systems of mainstream products, the advantage is obvious, however shortcomings business under the big data platform migration from SQL to NoSQL complex and high cost of the application to learnand unable to support the transaction and multi-dimensional index, many businesses can not enjoy from NoSQL systems of linear expansion of capacity. Google's internal MegaStore as a supplement of the Bigtable appear in the upper Bigtable support SQL, transactions, indexing, cross the room disaster recovery, and become famous Gmail APPEngine Android Market underlying storage. Therefore, we decided to explore how HBase system without sacrificing the linear expansion of capacity while providing interbank transactions, indexes, SQL function MegaStore for the theoretical model. Entrance through a simple user SQL, users do not need to concern hbase schema design, which greatly simplifies the user data migration and learning costs.To see what's supported, go to our language reference guide, and read more on our wiki.

Mission
====
Become a nosql system as a storage engine, for example the hbase, standard distributed relational database.

Note
====
Over a period of time, we will submit the code. Thank you for your attention.
