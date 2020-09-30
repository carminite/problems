In the Discord server [**apricot**](https://discord.gg/RUfcCkj), verification needs to happen for every single user to prevent any imposters from entering. Since no one really knows how to quickly verify everyone, the admin have set up a process: they send a string of ~N~ characters to each user, and have them figure out what's the lexicographically least and greatest substring with the following conditions:
* The substrings must start with a vowel.
* The substrings must end with a consonant.
* Anyone who considers `y` to be a vowel gets shanked.

Anyone who gets the answer right gets verified, and the rest are rejected.

Your friend, ~~afraid of getting shanked and~~ not being smart enough to do it, asks you to help him get verified in the form of a computer program.

### Input Specification
There will be two lines of input:
The first line will have an integer ~N~. The second will have a string of length ~N~.

### Output Specification
Print the lexicographically least substring on the first line, and the lexicographically greatest substring on the second.

### Sample Input
```
7
apricot
```

### Sample Output
```
ap
ot
```
