# apollo-connector-project-course
Airlock

## After Installation
This will run a graphQL service on port 4000

```
npm run rover config auth
```
```
cd apollo
```
```
../node_modules/.bin/rover dev \
  --supergraph-config ./supergraph.yaml \
  --router-config ./router.yaml
```


## To Install

```
npm run rover config auth
```

```
npm run rover -- init --path ./apollo
```


```
mkdir apollo
../node_modules/.bin/rover config auth
../node_modules/.bin/rover config whoami
## copy the key - leave the window open as we need the key later
../node_modules/.bin/rover config whoami
../node_modules/.bin/rover -- init --path ./apollo
## > Start a graph with one or more REST APIs
## ? Name your project: Odyssey Airlock
## For the next information look in the commandline for these lines
## GraphOS credentials for your graph
## APOLLO_GRAPH_REF=[aaa] (Formatted graph-id@variant, references a graph in the Apollo GraphOS platform)
## APOLLO_KEY=service:[bbb]] (This is your graph's API key)
## 
cd apollo
APOLLO_KEY=service:[bbb]\
APOLLO_GRAPH_REF=[aaa]] \
../node_modules/.bin/rover dev --supergraph-config supergraph.yaml
