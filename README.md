# deltaSharing

1. Databricks - Databricks
  - There are 2 workspaces Workspace_recieve and Worspace_sender
  - Worspace_sender > Catalog > Delta Sharing > Shared by Me > New Recipent > Sharing identifier (get unique identifier from Workspace_recieve delta sharing UI / current metastore())
  - Add Share data > Add table / catalogue to share / Notebook
  - Under Shared name > add recipient
  - Under Recipient > Grant share > choose data that you want to share
  - Workspace_recieve > Shared with me > Choose the Provider > Under shares > create catalog > Add catalog_name
  - In Workspace_recieve the shared data will be under the new catalog_name.

2. Databricks - External Tool
   - Lets name sender: Databricks and reciever: external (FME/coperleaf).
   - Make sure external delta sharing is enabled, by going to account console - catalog> metastore > toggle button 'Enable delta sharing'
   - Create Share and recipient like above, Add recipient to the share. (Choose Token, and its expiry date.)
   - Share activation link to recipient, download file with token.
   - Add the details in the external tool.
