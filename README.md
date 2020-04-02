To install postgres, follow instructions here: https://gist.github.com/ibraheem4/ce5ccd3e4d7a65589ce84f2a3b7c23a3

Then to create a database on your own machine:

```createdb petsdb```

You can then do:

```psql petsdb```

and 

```psql petsdb < create_tables.psql```


# Files to help you get started

create_tables.psql - will create the tables pets and food

insert.sql - will populate these tables with some rows

queries.sql - some example queries you can try

