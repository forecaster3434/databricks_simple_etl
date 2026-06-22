## 🚀 How to Connect This Repository to Databricks

Databricks AI/BI Dashboards are version-controlled inside this repository. Follow these steps to clone this repo into your Databricks workspace and start developing.

### Step 1: Generate a Personal Access Token (PAT)
Databricks needs permission to access your Git provider. 
1. Go to your Git provider settings (e.g., GitHub, GitLab, Azure DevOps).
2. Generate a new **Personal Access Token (PAT)** or SSH key.
   * *For GitHub:* Go to **Settings** > **Developer Settings** > **Personal Access Tokens (Tokens classic)**.
   * Select **repo** scopes/permissions.

### Step 2: Link Your Git Account to Databricks
1. Log into your **Databricks Workspace**.
2. Click your **User Profile** icon in the bottom-left corner and select **Settings**.
3. Navigate to the **Linked accounts** tab.
4. Under **Git credentials**:
   * Select your **Git provider**.
   * Enter your Git provider **username or email**.
   * Paste the **Personal Access Token (PAT)** you generated in Step 1.
5. Click **Save**.

### Step 3: Clone the Repository into Databricks
1. In the Databricks sidebar, click on **Workspace**.
2. Right-click on your user folder (under `Workspace` > `Users` > `your_email@domain.com`) or a shared folder.
3. Select **Create** > **Git folder**.
4. In the dialog box, fill in the following:
   * **Git repository URL:** Paste the HTTPS URL of this repository.
   * **Git provider:** Select your provider.
   * **Git folder name:** (Optional) Customize the folder name.
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
