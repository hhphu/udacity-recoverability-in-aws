# Single AZ outage
In an event of a single AZ outage, we can start a replica in a different zone (within the same region). This will takes about 2 minutes so the RTO is about 2 minutes.
Because the replica is already available and ready to be used, the RPO is about 1 or 2 minutes or, in some cases, can be considered 0 minute.

# Single region outage
In an event of a single region outage, we can refer to the secondary replica from different region. Time to swith to the secondary resources is approximately 5 to 10 minutes. Hence, the RTO is about 5 - 10 minutes.
Similar to the above scenearo, the RPO in this case will be about 5-10 minutes as it's the length for the secondary resources to be ready for usage.

 
