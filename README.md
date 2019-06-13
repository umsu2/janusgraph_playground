# janusgraph_playground
testing janusgraph

0. make sure install java 8, even java 9 is not supported.
1. run ./bin/janusgraph.sh start
2. run ./bin/greminlin.sh


3. `:remote connect tinkerpop.server conf/remote.yaml` to presist the info and not running in memory
` :remote console <- connect to remote console`
then somehow g will be defined same with graph.  


// alot of docs...
https://tinkerpop.apache.org/docs/current/reference/#graph

g.V(8232).addE("somestuff").to(V(16424))

 g.V(8232).addEdge("somestuff",V(16424)) DOESN"T WORK!!!!
 g.V(8232).next().addEdge('somestuffxxx', g.V(16424).next() ) will work
graphexp/graphexp.html to view
valueMap()
session
remote: start , stop

