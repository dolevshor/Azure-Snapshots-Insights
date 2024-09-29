# Azure Snapshots Insights

The 'Azure Snapshots Insights' workbook offers a comprehensive view of your Azure Snapshot resources.

This workbook designed to simplify monitoring and management of Azure Snapshots.

![image](https://github.com/user-attachments/assets/916d1333-77e8-4c50-9baa-f8ba69259570)


## Introduction

Managing snapshots in Azure can be challenging when you have large number of them across different Virtual Machines and subscriptions.
Over time, snapshots can accumulate, leading to increased storage costs and making it harder to identify which ones are still needed.

Read more in depth in this Tech Community blog: [Azure Snapshots: Simplify Management and monitoring](https://techcommunity.microsoft.com/)

## Benefits of using this workbook

- **Centralized Monitoring:** Manage all your snapshots in one place across multiple resource groups and subscriptions.
- **Cost Optimization:** Reduce storage expenses by identifying and deleting outdated snapshots.
- **Better Insights:** Gain a clearer understanding of your snapshot usage patterns by the inventory dashboard.

## Key Features

- Overview: Monitor important details like
  - Snapshot name
  - Source disk
  - Size (GiB)
  - Resource group
  - Location
  - Storage type
  - Snapshot type (Full/Incremental)
  - Time created
  - Public network access
  - Network Access Policy
  - Tags
- **Inventory:** Monitor the snapshot usage count by
  - Subscription Id
  - Resource Group
  - Location
  - Storage type
  - Source disk size (GiB)
  - Snapshot type
  - Disk state
  - Create Option
  - API Version
  - Public Network Access
  - Access policy
  - Data Access Auth Mode
- **Filtering:** Filter snapshots by specific subscription/s, resource group/s or specific resource/s.
- **Age-Based Filtering:** View snapshots by age creation (_1, 2, 3, 4, 5, 6 ,7, 14, 30, 60, 90 days ago_), making it easy to identify old ones.
- **Snapshot Deletion:** Remove outdated or unnecessary snapshots with just a few clicks directly from the workbook.

### Age-Based Filtering

To identify old snapshots you can use the 'Snapshot Age' filter.

![image](https://github.com/user-attachments/assets/8c4e931c-76bc-4dcb-9cb1-50d86cb89613)

- 'All Snapshots' will not apply a filter.
- 'x days ago' will apply the filter to present only snapshots older than x days.

### Snapshot Deletion
To enable the '⛔Delete Snapshot' option, you need first to enable it on the filter pane.

![image](https://github.com/user-attachments/assets/0d3d2419-a07b-4316-9e21-f5d47b2cc16f)

Now you can click on the '⛔Delete Snapshot' to delete the selected snapshot.

![image](https://github.com/user-attachments/assets/f770a82b-f689-4cfb-8529-5972bba8191b)

Please review the resource information thoroughly before continuing with the deletion.

![image](https://github.com/user-attachments/assets/4657444d-8962-462a-8a5c-29036105ec40)
