# Campus19EX

# change perissions to -r--r-xr-x
-r--r-xr-x
chmod u=r,o=xr,g=xr **file**

dr-x---r--
chmod u=rx,g=-r,o=r **file**

# make link nr
(dr-x---r-- **X**)
ln **file** **file**(to be created)

# change file bit size
truncate --size xx **file**

# change date of file
touch -a -m -t yyyymmddhhss **file**

