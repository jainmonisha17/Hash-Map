# Hash-Map
Given a string, identify the position of the first character that appears only once in the string. If no such character exists, return -1.

Why hashing?
Hashing is a great tool to quickly access, protect, and verify data. Here are a few of the common use cases of hashing:

Quick Data Retrieval: Hashing helps in accessing data super fast. With it, systems can quickly find a data piece without searching the whole database or list.

Data Integrity Checks: When downloading a file from the web, the site may provide you with a hash value for that file. If even a tiny portion of that file changes during the download, its hash will differ. By comparing the provided hash with the hash of the downloaded file, you can determine whether the file is exactly as the original, or if it was tampered with during the transfer

Password Security: Instead of storing actual passwords, systems store their hash. It's like locking the real magical item away and just keeping a hologram on display.

Hash Tables: Hashing is used in programming for efficient data structures like hash tables. It’s like having organized shelves for our books where each item has its designated spot.

Cryptography: Some hash functions are used in cryptography to ensure data confidentiality and integrity. It's like a spell that only allows certain wizards to read a message.

Data Deduplication: If you're saving data, and you don’t want duplicates, you can just compare their hashes. Same hash? It’s the same data. It ensures you're not wasting space with repeated magical items.

Load Balancing: In big systems serving many users, hashes can be used to decide which server should handle a particular request. It's like deciding which magical portal to send a wizard based on their wand.
