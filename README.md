# How to Run the Batch Producer
This will write the last day of transactions from midnight to the data directory, then write new transactions every hour.

Go to the project directory and run BatchProducerAppIntelliJ:
```
from root folder
sbt 
test:runMain coinyser.BatchProducerAppIntelliJ
```

# How to Run the Streaming Producer
This will send live transactions to a kafka topic "transactions".
```
from root folder
sbt 
test:runMain coinyser.StreamingProducerApp
```
