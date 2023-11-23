# Hashing
Image Hashing using PCA
Hashing is most commonly used to implement hash tables and for data encryption. A hash table stores key/value pairs in the form of a list, while the hash function maps the elements of the dataset via a key and generates hash values. A real-world recognition system has to cope with several unseen individuals and determine whether a given face image is registered or not, and thus, certain elements in databases can be found much faster-using hashing functions and classification methods

AIM:
Implement a basic hashing model from scratch that hashes the images

PROCEDURE
- Importing Libraries.
- Reading the dataset.
- Resize the image to a suitable size, followed by grayscale conversion of the image and Plotting them.
- Then mean normalize the image to obtain a binary image, whose sum can be used as a hash value.
- Using the hash model, encode all the images present inside the directory.
- Search for images similar to the query image.
