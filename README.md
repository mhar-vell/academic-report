# academic-report
This repository provides a model document (**report**) for the delivery of activities carried out during the development of an academic project.


The good presentation doc must have:
        
1. Introduction
2. Basis
3. Methods
4. Results and analysis
5. Conclusion

If you do not have Latex installed on your computer, follow the instructions below.

## Installing *TexLive*
To use this repo it is necessary to install *TexLive*.
    
```sh

    sudo add-apt-repository ppa:jonathonf/texlive
        
    sudo apt update
        
    sudo apt install texlive-full
       
    tlmgr install abntex2
        
    tlmgr update abntex2

```


### All cleaning *TexLive* (if necessary)

```sh

    sudo apt-get install ppa-purge

    sudo ppa-purge ppa:jonathonf/texlive

    sudo apt-get autoremove --purge tex-common texlive-base texlive-binaries texlive-common texlive-doc-base texlive-latex-base texlive-latex-base-doc

    sudo apt-get autoclean

```
