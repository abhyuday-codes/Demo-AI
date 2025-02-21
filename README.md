# **Steps to Insert or Update an Item in Sitecore Content Editor**

## **Important Note**
1. Each step must be performed **sequentially**, one at a time, before proceeding to the next step.
2. For each step instructions are given below the headline of that particular step, just follow those and perform operations in order.

## **Step 1: Open Sitecore Content Editor**
1. **Open** a web browser and navigate to the Sitecore Content Editor using the following URL in a **new tab**:  
   - **URL:** https://testautomation-cm.sitecoredemo.com/sitecore/shell/sitecore/client/Applications/Launchpad
2. **Enter** the following credentials to log in:
   - **Username:** `aiagent`
   - **Password:** `Altudo@12345`
3. **Scroll down** and locate the **Content Editor** option in the interface and open it.

## **Step 2: Navigate to the Content Tree**
1. **Locate** the **content tree panel** in the **Content Editor** which will be in leftbar of sitecore.
2. **Navigate** to the following path:
   - **Path:** `/sitecore/content/Demo SXA Sites/LighthouseLifestyle/home/People`

## **Step 3: Insert a New Item**
1. **Right-click** on the target folder.
2. **Select** **Insert → New Item** from the available options.
3. **Choose** the **appropriate template** for the new item, if insert options are shown other than "insert from template"
   then select appropriate one among them.
4. **Provide** a **meaningful name** for the item.
5. **Click** **OK** to finalize the item creation.

## **Step 4: Assign Content to Fields**
1. **Select** the **newly created item** in the content tree.
2. **Validate** in the **content section** according to the fields present in item:
   - **Title:** (no spell check required).
   - **Content:** (spell check required if field is present, if wrong then correct it)
   - **First Name:** (no spell check required).
   - **Last Name:** (no spell check required).
   - **Designation:** check for spelling and grammar.
   - **Location:** check for spelling and grammar.
   - **Email:** (no spell check required but check whether email format is correct or not).
   - **Image:** Select/upload an image from **query:$siteMedia**.
3. **Fill** in the **metadata section**:
   - **SEO Title:** Enter the SEO title and check for spelling and grammar.
   - **SEO Description:** Enter the SEO description and check for spelling and grammar.
4. **Click** **Save** to store the content changes.

## **Step 5: Assign Presentation Details**
1. **Navigate** to the **Presentation** tab in the Sitecore ribbon or top bar.
2. **Go to** **Details** and click on **Edit** for the MVC layout.
3. **Go to** **Controls** and select **Add**.
4. **Assign** the required **renderings and placeholders**.
5. **Click** **Select**.
6. **Go to** **Edit** and look for the **Rendering Variant**.
7. **Assign** the appropriate **Rendering Variant**.
8. **Click** **OK** to confirm changes.
9. **Click** **Save** to apply the presentation settings.

## **Step 6: Update Existing Item (If Already Created)**
1. **Check** if the item already exists in the **content tree**.
2. **Select** the existing item and **verify all fields**:
   - **Title:** Ensure correct spelling and grammar.
   - **Content:** Check for spelling and grammar.
   - **Designation:** Verify correct spelling and grammar.
   - **Location:** Ensure there are no spelling errors.
   - **SEO Title & Description:** Verify spelling and grammar.
3. **Check** if any field contains a **URL**:
   - **Ensure** that the link is relevant to the item’s details.
   - **Verify** that the link is **working and accessible**.
4. **Make necessary updates** and **click Save** to store the changes.

## **Step 7: Publish the Item**
1. **Navigate** to the **Publish** tab in the ribbon or top bar.
2. **Select** **Publish Item** from the dropdown on **Publish**.
3. **Choose** **Smart Publish** to apply all updates.
4. **Click** **Publish** to confirm and complete the publishing process.
