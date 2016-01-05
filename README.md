# shell-bin-tools

Handy linux shell scripts


## Recommended way to use this

**Login as your normal user**

**make sure you are in your $HOME**  
`cd ~;`

**create ~/bin if it doesn't exist**  
`mkdir -p ~/bin;`

**make sure this ~/bin dir is in your $PATH**  
*By default, upon opening a terminal or thru ssh, ~/bin will be added to the $PATH if it exists before you login. At this point, you can make sure ~/bin is in your $PATH by simply logging out and in again, or close the terminal and open it again, or by adding ~/bin now to $PATH, just like it's done in your ~/.profile file.*  
`PATH="$HOME/bin:$PATH";`

**go into that bin dir**  
`cd ~/bin;`

**clone this repo**  
`git clone http://github.com/ttc-solutions/shell-bin-tools;`

**link any script you want to use into your ~/bin**  
`ln -s shell-bin-tools/gen-pass ~/bin/gen-pass;`
