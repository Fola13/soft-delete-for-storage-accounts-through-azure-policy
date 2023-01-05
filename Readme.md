Hope you are looking for solution. 
Please upvote if helps. 


Azure policy to enable soft delete on storage accounts

To enable soft delete on a storage account in Azure, you can use Azure policy. Here are the steps you can follow:

Sign in to the Azure portal.
In the search box at the top of the portal, enter "Policy" and select "Policy" from the search results.
In the Policy blade, select the "Definitions" tab.
Click the "Add" button to create a new policy definition.
In the "Create a new policy definition" blade, enter a name for the policy, a description, and select "Storage" as the resource type.
In the "Rule" section, click the "Edit" button to open the "Edit policy rule" blade.
In the "Edit policy rule" blade, enter the rule from code file to enable soft delete on the storage account:

This policy will enable soft delete on the storage account and retain deleted blobs for 90 days. You can modify the number of days to retain deleted blobs by changing the value of the "days" field.

Click the "Save" button to save the policy definition.
To apply the policy to a storage account, select the policy definition and click the "Assign" button.
In the "Assign policy" blade, select the subscription and resource group where the storage account is located, and click the "Assign" button.
That's it! The policy will be applied to the storage account and soft delete will be enabled on it.
