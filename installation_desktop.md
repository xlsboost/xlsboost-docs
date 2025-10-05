XLSBoost Excel Add-in installation instructions for Microsoft Excel Desktop.

# Add-in #

1. Download the manifest into a file in a **Trusted Add-in Catalog**.

2. Click **"Home"** > **"Add-ins"** to open the "Add-ins" menu:

   ![Add-ins menu](images/installation_desktop/add_ins.png)

3. Click **"More Add-ins"** to open the "Office Add-ins" dialog.

4. Switch from the default **"Store"** view to the **"Shared folder"** view:

   ![Store view of Office Add-ins dialog](images/installation_desktop/office_add_ins-store.png)

   If the "Shared folder" view is missing, it means that there are no Trusted Add-in Catalogs registered yet. Fix by registering one as detailed below.

5. Choose the XLSBoost Excel Add-in from the list:

   ![Shared folder view of Office Add-ins dialog](images/installation_desktop/office_add_ins-shared_folder.png)

   If the list is empty, click "Refresh" to synchronize with Trusted Add-in Catalogs.

6. Wait for the XLSBoost Excel Add-in to load as a Taskpane App:

   ![Taskpane app](images/installation_desktop/taskpane_app.png)

# Trusted Add-in Catalog #

1. Create a **shared folder**:

   ![Shared folder](images/installation_desktop/shared_folder.png)

2. Click **"File"** > **"Options"**.

3. Select **"Trust Center"** from the left sidebar:

   ![Trust Center](images/installation_desktop/trust_center.png)

4. Click **"Trust Center Settings..."**.

5. Select **"Trusted Add-in Catalogs"** from the left sidebar:

   ![Trust Center Settings](images/installation_desktop/trust_center_settings.png)

6. Fill in **"Catalog Url"** by entering the UNC path to the previously created shared folder.

7. Click **"Add catalog"**.

8. Check **"Show in Menu"** on the newly added catalog entry.

   ![Trusted Catalogs Table](images/installation_desktop/trusted_catalogs_table.png)

9. Click **"OK"** to confirm changes.

10. Restart Excel.
