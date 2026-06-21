                 Merchants
                      |
                      |
              AWS Route53
                      |
                      |
         AWS Global Accelerator
                      |
      --------------------------------
      |                              |
      |                              |
Mumbai Region                 Hyderabad Region
ap-south-1                    ap-south-2

      |                              |
      |                              |
 Application Layer          Application Layer
      |                              |
      |                              |
 Aurora PostgreSQL      Aurora PostgreSQL
      |                              |
      |                              |
 DynamoDB Global Tables
      |                              |
      |                              |
 Redis Replication
      |                              |
      |                              |
 Kafka Cluster Replication