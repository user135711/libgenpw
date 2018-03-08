# libgenpw
outputs a curl config file containing the direct download urls that you can use with curl -K 

Uses curl and xmllint for html parsing


Usage : input output
  

Input is a database query output file in the format ID MD5 ( query must be select id,md5 from ...)
Output is the filename for the curl config file

Due to changes do libgen.pw the scripts no longer works
