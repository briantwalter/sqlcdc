## Todo's
- lots of stuff
- reminder to `confluent-hub` install the connector
- assumes docker is installed

## Example connector config POST
`curl -i -X POST -H "Accept:application/json" -H "Content-Type:application/json" http://localhost:8083/connectors/ -d @config.json.customers`

## Example connector install
`confluent-hub install debezium/debezium-connector-sqlserver:latest`
