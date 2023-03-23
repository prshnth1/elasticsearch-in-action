# elasticsearch-in-action
[Elasticsearch in Action (second edition) Book](https://www.manning.com/books/elasticsearch-in-action-second-edition?utm_source=mkonda&utm_medium=affiliate&utm_campaign=book_konda_elasticsearch_7_23_21&a_aid=mkonda&a_bid=edbc50d4)

The [book's accompanying wiki pages](https://github.com/madhusudhankonda/elasticsearch-in-action/wiki) explains the code examples 

Here's the TOC 

1. Overview
2. [Getting Started](https://github.com/madhusudhankonda/elasticsearch-in-action/wiki/Ch-2:-Getting-Started)
2. [Architecture](https://github.com/madhusudhankonda/elasticsearch-in-action/wiki/Ch-3:-Architecture)
4. [Mapping](https://github.com/madhusudhankonda/elasticsearch-in-action/wiki/Ch-4.-Mapping)
5. [Working with Documents](https://github.com/madhusudhankonda/elasticsearch-in-action/wiki/Ch-5.-Document-Operations)
6. [Indexing Operations](https://github.com/madhusudhankonda/elasticsearch-in-action/wiki/Ch-6-Indexing-Operations)
7. [Appendix A: Installing and configuring Elasticsearch and Kibana](https://github.com/madhusudhankonda/elasticsearch-in-action/wiki/Appendix-A:-Installation)

## Disabling XPack Security for 8.x
By default, 8.x version of Elasticsearch comes with security enabled. For simplicity and not getting the security in our way, we can disable the feature

> :warning: **PLEASE DO NOT disable security in PRODUCTION**

Edit config/elasticsearch.yml to add the following property at the end of the file:
```xpack.security.enabled: false```
