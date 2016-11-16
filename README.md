# nluug-2016-minimesos

Slides and demo for the [minimesos talk at the NLUUG 2016 Fall Conference](https://www.nluug.nl/activiteiten/events/nj16/abstracts/ab11.html)

```
$ minimesos up
```

Check out the *Frameworks* tab. Elasticsearch should be running. From here you can check out the tasks and scale up or down.

```
$ docker ps
$ cat minimesosFile
$ cat es.json
$ minimesos up
```

Check out the master UI
Click frameworks tab

```
$ minimesos state | less
```

Find executor IP and port

```
$ curl -XPUT -d@tweet.json IP:PORT/twitter/tweet/1
```

Go to the UI
Perform a search
Scale up
Perform a search again
Check out the `_nodes` endpoint

```
$ cd .minimesos
```

Check the contents of the `sandboxes-*` folders

```
$ minimesos destroy
$ docker ps
```



