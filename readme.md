# serializable_trie
This is a library for the trie data structure which can be converted tofrom a list of strings.
a user can do the following

1. Create a trie using a list of words or an empty trie.
2. insert words to the trie.
3. convert the trie to a list of words.
4. check how many words in the trie have a given prefix.
5. check if a given word is present in the trie.
6. Convert the trie to a string i.e. serialize the trie.
7. Create a trie using a string representing the trie.

Note Serialization of the trie to a string makes use of special characters '>' and ']'. The user is expected to not use these symbols in words that are to be inserted to the trie.

written in c++.
