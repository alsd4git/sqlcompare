# sqlcompare
simple shell script to compare two SQL create tables


to start:
```sh
git clone https://github.com/alsd4git/sqlcompare
cd dotfiles
chmod a+x SqlCompare.sh
```

I usually just use it with 
```sh
sh SqlCompare.sh old_db.sql new_db.sql 1
```

this script was written on a windows machine using git bash, but it should work on plain bash with no problems, you can use ```"SqlCompare.sh -h``` to get a simple help