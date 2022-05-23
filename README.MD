```DEVELOPING A SUBGRAPH```

# To build a descentralized API with The Graph, a developer creates a subgraph that defines:
-The data source
<br>
-The data that should be indexed
<br>
-Events you want to listen
<br>
-Resolvers when events are emmited

<br>
<br>

# As a developer you only have to work with three files:

<br>
1- Manifest = subgraph.yaml (Start block, Entity names (Objects in your schema you are querying for), events or events handlers)
<br>
2- Schema.graphql = @entity'sS
<br>
3- AssemblyScript Mappings 



Next steps:

  1. Run `graph auth` to authenticate with your deploy key.

  2. Type `cd Chainlink` to enter the subgraph.

  3. Run `yarn deploy` to deploy the subgraph.




```Subgraph endpoints:```
1. Queries (HTTP):     https://api.thegraph.com/subgraphs/name/jacevezh1/chainlink
2. Subscriptions (WS): wss://api.thegraph.com/subgraphs/name/jacevezh1/chainlink