# someta3_datamodel

```
java -jar /Users/stefan/apps/ili2pg-4.7.0/ili2pg-4.7.0.jar --dbhost localhost --dbport 54324 --dbdatabase meta --dbusr postgres --dbpwd postgres --createBasketCol --defaultSrsCode 2056 --createMetaInfo --strokeArcs --modeldir . --models Meta_V0_1 --dbschema meta --schemaimport
```

```
java -jar /Users/stefan/apps/ili2pg-4.7.0/ili2pg-4.7.0.jar --dbhost localhost --dbport 54324 --dbdatabase meta --dbusr postgres --dbpwd postgres --modeldir . --models Meta_V0_1 --dbschema meta --export connection.xtf
```

```
java -jar /Users/stefan/apps/ili2pg-4.7.0/ili2pg-4.7.0.jar --dbhost localhost --dbport 54324 --dbdatabase meta --dbusr postgres --dbpwd postgres --createBasketCol --defaultSrsCode 2056 --createMetaInfo --strokeArcs --modeldir . --models Meta_V0_1 --dbschema meta --importBid --doSchemaImport --import connection.xtf
```
