# api-microservices-Contract-test.

### first start local kafka docker (start the pact-broker) with:
```sudo docker-compose up -d```

### Run the contract test using below maven command

``` mvn clean install ```

### Paste the pact-broker url in browser.

```http://localhost:9090```

### After successfully Running contract test, then publish the generated pact into Pact-Broker.

```mvn pact:publish ```
