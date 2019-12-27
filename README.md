# wlist
A collection of passwords and wordlists commonly used for dictionary-attacks using a variety of password cracking tools such as aircrack-ng, hydra and hashcat.

## Useful one-liners for wordlist manipulation
**Remove duplicates**
```
awk '!(count[$0]++)' old.txt > new.txt
```
**Sort by length**
```
awk '{print length, $0}' old.txt | sort -n | cut -d " " -f2- > new.txt
```

**Sort by alphabetical order**
```
sort old.txt | uniq > new.txt
```
**Merge multiple text files into one**
```
cat file1.txt file2.txt > combined.txt
```

**Remove all blank lines**
```
egrep -v "^[[:space:]]*$" old.txt > new.txt
```
https://drive.google.com/file/d/19O7WanShcBNTymso-0jnb0-lLVs6_TYL/view?usp=sharing
