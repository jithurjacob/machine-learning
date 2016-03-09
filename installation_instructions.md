# Installation Instructions for the workshop


### Package Manager: Anaconda

We strongly recommend using Anaconda. It can be downloaded from here:
https://www.continuum.io/downloads

It comes with `jupyter notebook` which is the IDE we will be using for the workshop

We recommend using the Python 3.5 version.

### Required packages

Run the following script at the command prompt to check if you have all the requisite packages are installed.
To run, please execute the following command from the command prompt

    ```$ python check_env.py```

The output will indicate if any of the libraries are missing or need to be updated. 

Any package that is missing can be installed by running the command at the command prompt

    ```$ pip install <package_name> ```

Replace **<package_name>** with the package that needs to be installed. 

After all the packages are installed, please run the following two commands

1. Install all the corpora for the `nltk` module. Please be warned that this is a huge file and can take a while. Please refer http://www.nltk.org/data.html for further information on what it downloads

    ```$ python -m nltk.downloader all```

2. Install all the corpora for the `spacy` module. Please be warned that this is a huge file and can take a while

    ```$ python -m spacy.en.download```




