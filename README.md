# Multi-Threaded Zipfile Cracker #


```
usage: mtzc.py [-h] [--file FILE] [--passwords PASSWORDS] [--threads THREADS] [--verbose]

options:
  -h, --help            show this help message and exit
  --file FILE, -f FILE  zip file to crack
  --passwords PASSWORDS, -p PASSWORDS
                        passwords wordlist to use
  --threads THREADS, -t THREADS
                        threads to work with (default: 2000)
  --verbose, -v         verbosing the bruteforcing attempts (affects the program's performance)

(M)ulti (T)hreaded (Z)ipfile (C)racker
```

- example:

`mtzc.py -f 'file.zip' -w wordlist.txt -t 2000`