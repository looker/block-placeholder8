# Xero Block #
## What Does This Block Do For Me? ##

This block will take your exported Xero data and bring familiar metrics to life in your Looker instance.

## Content ##
#### Explores ####
* ar_history - Accounts Receivable History
* xero_contact - Xero User-Centric Information
* xero_general_ledger - Main Explore joining components in respect to the General Ledger
* xero_invoice - Invoice Focused explore.

#### Dashboards ####
* Xero Dashboard - Replicates the metrics available in your Xero Dashboard
* Accounts Receivable - Pertinent information for Current, Past Due, and Historical Accounts Receivable Information.

## Installation ##
This block is installed via the Looker Marketplace. For more information about the Looker Marketplace, please visit this [link](https://docs.looker.com/data-modeling/marketplace).

#### Constants ####
During installation you will provide two values to populate the following constants:
* Connection Name - the Looker connection with access to and permission to retrieve data from your exported Xero tables.
* Xero Schema - the schema name for your Xero tables.

#### Customization ####
- This block uses Refinements to allow for modification or extension of the LookML content. For more information on using refinements to customize marketplace blocks, please see [this documentation](https://docs.looker.com/data-modeling/marketplace/customize-blocks).
