- DynamoDB is a NoSQL fully managed Database-as-a-Service (DBaaS) product available within AWS.

![alt text](image-56.png)

![alt text](image-57.png)

![alt text](image-58.png)

![alt text](image-59.png)

![alt text](image-60.png)

![alt text](image-61.png)

![alt text](image-62.png)

![alt text](image-63.png)

![alt text](image-64.png)

![alt text](image-65.png)

![alt text](image-66.png)

- Local Secondary Indexes (LSI) and Global Secondary Indexes (GSI) allow for an alternative presentation of data stored in a base table.

- LSI allow for alternative SK's whereas with GSIs you can use alternative PK and SK.

![alt text](image-67.png)

![alt text](image-68.png)

![alt text](image-69.png)

![alt text](image-70.png)

![alt text](image-71.png)

![alt text](image-72.png)

- DynamoDB Streams are a 24 hour rolling window of time ordered changes to ITEMS in a DynamoDB table

- Streams have to be enabled on a per table basis , and have 4 view types

- KEYS_ONLY

- NEW_IMAGE

- OLD_IMAGE

- NEW_AND_OLD_IMAGES

- Lambda can be integrated to provide trigger functionality - invoking when new entries are added on the stream.

![alt text](image-73.png)

![alt text](image-74.png)

![alt text](image-75.png)

![alt text](image-76.png)

- DynamoDB Global Tables provides multi-master global replication of DynamoDB tables which can be used for performance, HA or DR/BC reasons.

![alt text](image-77.png)

![alt text](image-78.png)

- DynamoDB Accelerator (DAX) is an in-memory cache designed specifically for DynamoDB. It should be your default choice for any DynamoDB caching related questions.

![alt text](image-79.png)

![alt text](image-80.png)

![alt text](image-81.png)

- Amazon DynamoDB Time to Live (TTL) allows you to define a per-item timestamp to determine when an item is no longer needed.
- Shortly after the date and time of the specified timestamp, DynamoDB deletes the item from your table without consuming any write throughput. TTL is provided at no extra cost as a means to reduce stored data volumes by retaining only the items that remain current for your workload’s needs

![alt text](image-82.png)

 ![alt text](image-10.png)

 ![alt text](image-11.png)
 
 ![alt text](image-12.png)
 
 ![alt text](image-13.png)
 
 ![alt text](image-14.png)
 
 ![alt text](image-15.png)
 
 ![alt text](image-16.png)
 
 ![alt text](image-17.png)
 
 ![alt text](image-18.png)
 
 ![alt text](image-19.png)
 
 ![alt text](image-20.png)