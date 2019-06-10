# Attivio Platform SDK 5.2

```text
NOTE: This is the SDK branch for Attivio 5.2.  Other versions can be accessed via the appropriate branch above.
```

## Attivio SDK

To get started using the SDK, use Maven \(`mvn`\) to generate a sample client project or module. Attivio modules allow custom code \(most commonly ingestion or query transformers\) to be added to your Attivio projects. An Attivio client project contains code that connects to an existing Attivio system and ingests data, runs queries, or uses other public APIs.

### Create a sample Attivio module

```text
mvn archetype:generate -DarchetypeGroupId=com.attivio.platform.archetypes -DarchetypeArtifactId=attivio-archetype-module -DarchetypeVersion=5.2.6.6
```

[Attivio Module SDK](https://github.com/attivio/sdk/blob/5.2/attivio_module_sdk.md)

### Create a sample Attivio client project

```text
mvn archetype:generate -DarchetypeGroupId=com.attivio.platform.archetypes -DarchetypeArtifactId=attivio-archetype-client -DarchetypeVersion=5.2.6.6
```

[Attivio Client SDK](https://github.com/attivio/sdk/blob/5.2/attivio_client_sdk.md)

### Other guides

[Writing and Testing Custom Components](https://github.com/attivio/sdk/blob/5.2/writing_and_testing_components.md)

