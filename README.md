# mathias-gilles

## Practice 2

### Create NameSpace

````shell
sh bin/create_guestbook_ns.sh
````

### Create redis services & deployment

````shell
kubectl apply -f redis
````

### Create front service & deployment

````shell
kubectl apply -f front
````