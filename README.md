```
mvnrun artifact [args]
       calculate a classpath for an artifact and either print it or run java with it
       artifact (required) in group:id[:version] notation, default version is LATEST
       args -> run java -cp $cp ${@:2}, otherwise print the classpath
       eg:
           mvnrun org.db4j:kilim kilim.examples.SimpleTask
```

### installation

place the `mvnrun` script on your path or if you have npm on your path, use `npm install -g mvnrun`

