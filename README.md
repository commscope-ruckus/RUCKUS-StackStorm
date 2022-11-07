# RUCKUS-StackStorm

Installation instructions for SmartZone and ICX integration packs:

untar the files

cd to the directory of the uncompressed files

execute the following commands:

$ git init

$ git add ./*

$ git commit -m 'Release 1.0'

$ st2 login admin -p <password> 

$ st2 pack install file://$PWD
