# NLP-finalProject

### MOTIVATION AND BACKGROUND
• goal-oriented dialog systems, a.k.a virtual assistants (VAs), often fail to
   recognize the intent of natural language requests
• in practice, these cases are normally identified using intent classifier
   uncertainty – requests that are predicted to have a level of confidence below a
   certain threshold are reported as unrecognized (or unhandled)
• unhandled requests carry over various aspects of potential importance
• in large deployments the number of unhandled requests can reach tens of
   thousands daily, making manual inspection impractical

• our goal is to propose (and implement) an approach for
• (1) surfacing topical clusters in unhandled requests (clustering)
• (2) cluster naming (labeling)

### CLUSTERING REQUESTS – requirements
Clustering solutions can be roughly categorized into across two major dimensions:
• requiring a predefined (fixed) number of output clusters
• forcing cluster assignment on the entire dataset
(the K-MEANS clustering)
VS
• discovering the number of clusters as part of the clustering algorithm
• tolerating outliers
(required in our use-case)

### EVALUATION
• (1) surfacing topical clusters in unhandled requests (clustering)
• multiple dataset(s) with (good) clustering solution will be provided as a ground truth
• quantitative evaluation
• (2) cluster naming (labeling)
• example assignment of cluster names will be provided
• qualitative evaluation

### CLUSTERING EVALUATION: GROUND TRUTH IS KNOWN
• rand index (RI) and adjusted rand index (adjusted RI)
• the number of un-clustered instances
• the number of clusters
