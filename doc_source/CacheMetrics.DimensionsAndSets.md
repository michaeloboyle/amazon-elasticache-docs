# Dimensions for ElastiCache Metrics<a name="CacheMetrics.DimensionsAndSets"></a>

 All ElastiCache metrics use the `AWS/ElastiCache` namespace and provide metrics for a single dimension, the `CacheNodeId`, which is the automatically\-generated identifier for each cache node in the cache cluster\. You can find out what these values are for your cache nodes by using the `DescribeCacheClusters` API or describe\-cache\-clusters command line utility\. For more information, see [DescribeCacheClusters ](http://docs.aws.amazon.com/AmazonElastiCache/latest/APIReference/API_DescribeCacheClusters.html) in the *Amazon ElastiCache API Reference* and [ describe\-cache\-clusters](http://docs.aws.amazon.com/cli/latest/reference/elasticache/describe-cache-clusters.html) in the *AWS Command Line Interface Reference*\.

Each metric is published under a single set of dimensions\. When retrieving metrics, you must supply both the `CacheClusterId` and `CacheNodeId` dimensions\. 

**Contents**

+ 

+ 

+ 

+ [Which Metrics Should I Monitor?](http://docs.aws.amazon.com/AmazonElastiCache/latest/UserGuide/CacheMetrics.WhichShouldIMonitor.html)