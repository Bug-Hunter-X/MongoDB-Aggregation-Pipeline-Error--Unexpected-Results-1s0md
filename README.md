# MongoDB Aggregation Pipeline Bug

This repository demonstrates a common error in MongoDB aggregation pipelines that results in unexpected query results. The issue stems from an incorrectly ordered pipeline, leading to inaccurate grouping and sorting.

## Bug Description

The original aggregation pipeline attempts to group documents, sort by count, and limit the results to the top 10. However, due to the incorrect ordering or missing stages, the pipeline returns incorrect results.

## Solution

A corrected pipeline is provided, ensuring that the stages are appropriately ordered and any necessary stages are included for accurate results.  This corrected pipeline addresses the efficiency issues as well.