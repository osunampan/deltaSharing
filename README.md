# deltaSharing

1. Databricks - Databricks
  - There are 2 workspaces Workspace_recieve and Worspace_sender
  - Worspace_sender > Catalog > Delta Sharing > Shared by Me > New Recipent > Sharing identifier (get unique identifier from Workspace_recieve delta sharing UI / current metastore())
  - Add Share data > Add table / catalogue to share / Notebook
  - Under Shared name > add recipient
  - Under Recipient > Grant share > choose data that you want to share
  - Workspace_recieve > Shared with me > Choose the Provider > Under shares > create catalog > Add catalog_name
  - In Workspace_recieve the shared data will be under the new catalog_name.
