# Custom VM Summary Dashboard for vRealize Operations 7.0 and 7.5
---------

This dashboard is designed to replace the out of the box summary dashboard for Virtual Machine objects in [vRealize Operations](https://www.vmware.com/products/vrealize-operations.html).  It's intended to give a high level overview of a virtual machine by showing alerts, capacity, and performance KPIs to help quickly identify areas of concern for additional troubleshooting.

## Dashboard
![Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-custom_vm_summary/master/Dashboard.png)

## Installation
1. Import the dashboard at `Dashboards` / `Actions` / `Manage Dashboards` / `Import Dashboards`.
    ![Import Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-custom_vm_summary/master/Import_Dashboard.png)
2. Click `Browse...` then select the file named [Dashboard - Custom VM Summary.zip](https://github.com/notoriousbdg/vrops-dashboard-custom_vm_summary/raw/master/Dashboard%20-%20Custom%20VM%20Summary.zip)
3. The dashboard should now be available in in the dashboard list. **Note:** The dashboard should show as disabled as it will not be usable as a typical dashboard.
    ![Dashboard List](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-custom_vm_summary/master/Dashboard_List.png)
4. Click the gear icon then select `Manage Summary Dashboards`.
    ![Manage Summary Dashboards](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-custom_vm_summary/master/Dashboard_Manage_Summary_Dashboards.png)
5. Search for `Virtual Machine`, select `Virtual Machine`, then click `Assign a dashboard`.
    ![Assign Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-custom_vm_summary/master/Dashboard_Assign_Summary_Dashboard.png)
6. Select `Custom VM Summary` dashboard from the list then click `OK`.
    ![Select Dashboard](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-custom_vm_summary/master/Dashboard_Selected_Summary_Dashboard.png)
7. Click `Save`.
    ![Complete](https://raw.githubusercontent.com/notoriousbdg/vrops-dashboard-custom_vm_summary/master/Dashboard_Summary_Dashboard_Complete.png)
8. Navigate to a Virtual Machine and view the new custom summary dashboard.

## Support

This dashboard requires vRealize Operation 7.0 or 7.5 Advanced or Enterprise edition.

Please open an [issue](https://github.com/notoriousbdg/vrops-dashboard-custom_vm_summary/issues) for feedback.
