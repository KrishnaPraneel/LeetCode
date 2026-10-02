49. Group Anagrams

I use a hashmap where the key is the character frequency count of a word. I create an array of size 26 and count how many times each letter appears. Two words are anagrams if they have identical frequency counts, so they will produce the same key. Since lists cannot be dictionary keys, I convert the count array to a tuple. Finally, I return all the grouped values.
