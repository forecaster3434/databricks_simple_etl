## DESCRIPTION

univerisity project 

databricks simple etl with dashboard for reporting the potential best matches for the UFC fights

fetching the kaggle api for truncate-insert load of ufc fighters performance statistics dataset as source,

transforming it following medallion architecture 

reporting using bubilt in databricks dashboard ui fucntionality 
## 🚀 How to Connect This Repository to Databricks (No Tokens Required)

Databricks AI/BI Dashboards are version-controlled inside this repository. Follow these steps to authorize Databricks using your GitHub account login.

### Step 1: Install the Databricks App in GitHub
1. Go directly to the official [Databricks GitHub App Page](https://github.com) (or your company's dedicated Databricks GitHub enterprise application).
2. Click **Install**.
3. Select your GitHub account or Organization.
4. Choose **All repositories** or select **Only select repositories** (and check this specific dashboard repo).
5. Click **Install & Authorize**.

### Step 2: Link Your GitHub Account in Databricks
1. Log into your **Databricks Workspace**.
2. Click your **User Profile** icon in the bottom-left corner and select **Settings**.
3. Navigate to the **Linked accounts** tab.
4. Click **Add Git credential**.
5. Change the provider to **GitHub**.
6. Select **Link Git account** (OAuth login) and click **Link**.
7. A GitHub window will pop up. Click **Authorize Databricks** to finalize the link.

### Step 3: Clone the Repository into Databricks
1. In the Databricks sidebar, click on **Workspace**.
2. Right-click on your user folder (under `Workspace` > `Users` > `your_email@domain.com`) or a shared folder.
3. Select **Create** > **Git folder**.
4. Paste the HTTPS URL of this GitHub repository into the **Git repository URL** box.
5. Click **Create Git folder**.

---

## 📊 Managing Dashboards inside Databricks

Once cloned, you will see the dashboard file(s) inside your new Databricks Git folder.

### Making Changes & Syncing
1. **Open and Edit:** Click on the dashboard asset inside your Databricks Git folder to open it and make your edits.
2. **Commit Your Changes:** 
   * Click the **Git branch button** at the top-left of your opened dashboard or Git folder view.
   * Write a commit message.
   * Click **Commit & Push** to sync your changes back to this remote repository.
3. **Pulling Updates:** If someone else updates the dashboard, click the Git branch button in Databricks and click **Pull** to get the latest version.
