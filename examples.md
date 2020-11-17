
* Searching:
- curl '127.0.0.1:9200/_all/_search?q=abstract:gender&pretty'

* Adding to index:
- curl -H "Content-Type: application/json" -XPUT 'localhost:9200/[index]/_doc/[#id]' -d '{}'
