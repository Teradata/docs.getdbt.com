---
title: "Connect Teradata"
id: connect-Teradata
description: "Configure Teradata connection."
sidebar_label: "Connect Teradata"
---

The dbt-teradata adapter is maintained by the Teradata team. The Teradata team is committed to supporting and improving the adapter over time, so you can be sure the integrated experience will provide the best of dbt and the best of Teradata.

## About the dbt-teradata adapter

dbt-teradata is compatible with the following versions of dbt Core in dbt Cloud.

| Feature      | dbt Versions                                 |
|--------------|----------------------------------------------| 
| dbt-teradata | Available starting with dbt 1.8 in dbt Cloud |


To set up the Teradata connection, At a minimum, you need to specify host, user, password, schema (database), tmode

| Field    | Description                                     |
|----------|-------------------------------------------------|
| Host     | hostname of the Teradata database to connect to |
| user     | Username for the database login                 |
| password | Password for the user login                     |
| Schema   | Schema or Database name                         |
| Tmode    | ANSI or TERA                                    |


---   Screenshot from dbt-cloud goes here, showing the connection parameter for teradata connection

The logon mechanism for Teradata jobs that dbt executes can be configured with the logmech configuration in your Teradata profile. The logmech field can be set to: TD2, LDAP, BROWSER, KRB5, TDNEGO. For more information on authentication options, go to [Teradata Vantage authentication documentation](https://docs.teradata.com/r/8Mw0Cvnkhv1mk1LEFcFLpw/0Ev5SyB6_7ZVHywTP7rHkQ).

To learn how to optimize performance with data platform-specific configurations in dbt Cloud, refer to [Teradata-specific configuration](https://docs.getdbt.com/reference/resource-configs/teradata-configs).
