# Python Rest Client Schema Registry

[![Build Status](https://travis-ci.org/marcosschroh/python-schema-registry-client.svg?branch=master)](https://travis-ci.org/marcosschroh/python-schema-registry-client)
[![GitHub license](https://img.shields.io/github/license/marcosschroh/python-schema-registry-client.svg)](https://github.com/marcosschroh/python-schema-registry-client/blob/master/LICENSE)


Python Rest Client to interact against [schema-registry](https://docs.confluent.io/current/schema-registry/index.html) confluent server to manage [Avro Schemas](https://docs.oracle.com/database/nosql-12.1.3.1/GettingStartedGuide/avroschemas.html) resources.

## Requirements

python 3.6+, avro-python3, fastavro, requests

## Installation

```
pip install python-schema-registry-client
```

## Client API, Serializer, Faust Integration and Schema Server descriptiom

[Client API](../master/docs/client.md)

[Message Serializer](../master/docs/serializer.md)

[Schema Registry Server Description](../master/docs/schemaregistry_server.md)

[How to use if with Faust?](../master/docs/faust.md)

