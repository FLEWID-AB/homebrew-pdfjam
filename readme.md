# How to Install
* `brew tap FLEWID-AB/homebrew-pdfjam`
* `brew install pdfjam`
* You need MacTex. Download it here `https://tug.org/mactex/mactex-download.html`
* After installation of MacTex, you need to export your pdflatex path. You can find the executable by searching for it. `sudo find -name pdflatex`. For me it was `/usr/local/texlive/2017/bin/x86_64-darwin`
* `nano ~/.bash_profile` then add the path you just got from search. example: `export PATH=/usr/local/texlive/2017/bin/x86_64-darwin:$PATH` and `. ~/.bash_profile`. After that you should be able to use pdfjam.
