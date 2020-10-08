# wlist
A collection of passwords and wordlists commonly used for dictionary-attacks using a variety of password cracking tools such as aircrack-ng, hydra and hashcat.
this list contain from 0 to 5 

```
Command is :crunch 0 5 0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ -o word.txt
```


https://drive.google.com/file/d/1v69rgs5cngYUVMF-8Rfu26NBjbPrANH3/view?usp=sharing

```
FILE SIZE :  5 GB (5,572,596,953 bytes)
```

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

