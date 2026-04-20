# OAuth Integration Apps
                                                                                                                                                                                 
  Apps that read from the **Databricks Bakehouse** and **Snowflake Staging** databases                                                  
                                                                                                                                                                                 
  ## Required Environment Variables                                                                                                                                              
                                                                                                                                                                                 
  ### Databricks                                                                                                                                                                 
                                                                                                                                                                                 
  | Variable         | Description                                   |
  | ---------------- | --------------------------------------------- |                                                                                                      
  | `DATABRICKS_PATH` | SQL warehouse HTTP path (see below)          |
                                                                                                                                                                                 
  **How to find `DATABRICKS_PATH`:**                                                                                                                                             
                                                                                                                                                                                 
  1. Log in to Databricks                                                                                                                                                        
  2. Navigate to **SQL Warehouses**                                   
  3. Select your warehouse and open the **Connection Details** tab                                                                                                               
  4. Copy the **HTTP path** value
                                                                                                                                                                                 
  ### Snowflake                                                       
                                                                                                                                                                                 
  Snowflake Staging environment variables are stored in **1Password**:

  > **1Password → Snowflake → Staging → Env Variables**
                                                                                                                                                                                 
  Required variables:
                                                                                                                                                                                                                            
  - `SNOWFLAKE_WAREHOUSE`                                                                                                                                                        
  - `SNOWFLAKE_DATABASE`
  - `SNOWFLAKE_SCHEMA`                                                                                                                                                           
                                                                                                                                                                                 
  ### Integration Discovery (find-by-name variants only)
                                                                                                                                                                                 
  - `SNOWFLAKE_INTEGRATION_NAME` — name of the Snowflake OAuth integration on Connect
  - `DATABRICKS_INTEGRATION_NAME` — name of the Databricks OAuth integration on Connect       
