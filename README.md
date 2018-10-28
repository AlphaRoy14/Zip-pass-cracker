# Zip-pass-cracker

Multi threaded, dictionary based zip file password cracker 

## Using 
Run the program in terminal while specefying the zipfile and the word dictionary

```
python zip-pass-cracker.py -f <zip file> -d <dictionary>

```

## Built With

* [zipfile](https://docs.python.org/3/library/zipfile.html) - The library to extract zipped files
* [optparse](https://docs.python.org/2/library/optparse.html) - To for getting command line arguments
* [threading](https://docs.python.org/3/library/threading.html) - For multi threading
