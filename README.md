Installation:

Make a git checkout on your fortune directory (/usr/share/games/fortunes in Ubuntu 12.04):

$ git clone https://github.com/viniciusah/fortune-entrepreneurship entrepreneurship

Above command may require sudo if you dont have write permission on your fortune directory


To include quotes:

Edit the file without .dat extension (choose the language of your quote). The sintax is very simple. After save the file use the following command to generate a new .dat file

$ strfile quotefile quotefile.dat


Usage:

For english quotes:

$ fortune entrepreneurship

Para frases em português brasileiro:

$ fortune entrepreneurship/entrepreneurship.ptBR
