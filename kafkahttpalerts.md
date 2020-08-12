# Raw JSON Alert from Cloudera SMM

{"id":"87884fcd-d036-4b1d-8ce8-7da92e7804ef",
"payload":"Alert policy : \"ALERT IF ( PRODUCER (name=\"nifi-prices-api-producer\") IS_PRODUCER_ACTIVE != true )\" has been evaluated to true\n\nCondition : \"IS_PRODUCER_ACTIVE!=true\" has been evaluated to true for following PRODUCERS \n   - PRODUCER = \"nifi-prices-api-producer\"  had following attribute values\n          * IS_PRODUCER_ACTIVE = false\n",
"headers":
{"cluster.id":"Tr57HLZWS_eG8D7GvZRU9Q"},
"alertPolicyId":4,
"alertName":"alert4",
"notifierInstanceIds":[1],
"rootResource":
{"type":"PRODUCER","name":"nifi-prices-api-producer"},
"resolvedResources":
[{"type":"PRODUCER","name":"nifi-prices-api-producer"}],
"state":"RAISED",
"createTimestamp":1597244175169,
"updateTimestamp":1597244475245}

