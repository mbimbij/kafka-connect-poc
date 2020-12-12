https://docs.confluent.io/kafka-connect-jdbc/current/source-connector/source_config_options.html#jdbc-source-configs
https://kafka.apache.org/documentation/#connect
curl -i -X POST -H "Accept:application/json" -H  "Content-Type:application/json" http://localhost:8080/connectors/ -d @register-mysql.json -w "\n"
