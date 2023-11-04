# java-cli-millbuild-dolt-hibernate-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- java
- millbuild
  - hibernate
  - hql
  - log4j
  - dolt driver

## Docker stack
- nightscape/scala-mill
- dolthub/dolt-sql-serverdb

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
