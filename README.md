# KataCurl-ElasticSearch
KataCurl ElasticSearch Scripts

### USAGE

    export ES_URL_FROM="http://url_es_src:9200"
    export ES_URL_TO="http://url_es_dest:9200"
    export ES_INDEX=test
    
    export ES_INDEX_FROM=test  #OPTION
    export ES_INDEX_TO=test2   #OPTION
    
    /bin/sh -c es.mappings.katacurl.sh

### COMPATIBILITY

KataCurl Version | Release Date | Component  
------------------ | ------------ | ------------------- 
0.1.5-5            | 2015-05-14   | [ES 1.5.2](https://www.elastic.co/downloads/elasticsearch)
0.1.5-5            | 2015-05-14   | [JQ 1.5rc1](http://stedolan.github.io/jq)

### LICENCE
* GNU GENERAL PUBLIC LICENSE 2

### CREDITS
* http://stedolan.github.io/jq/

### Build 0.1.5-5
Release Date: 14 may 2015

* add option index src and index dest
* add shl/json/sample.json (TODO)
* es.katacurl.mappings.sh
