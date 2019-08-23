# Facebook Token Instructions

## Create Apps and Tokens
Below are the instructions to create a facebook token for your page.

1. Login to Facebook using a Desktop Computer. **IMPORTANT:** Login using an account that has admin rights to the Facebook page your would like to pull posts from.

![Facebook Developer Menu](../images/developer-facebook-menu.png)

2. Click on Add New App.

![Create App Link](../images/create-app-link.png)

3. Fill the Display Name and Contact Email and click Create App ID

![New App ID](../images/create-new-app-id.png)

4. After creating the application, go to [https://developers.facebook.com/tools/explorer](https://developers.facebook.com/tools/explorer).

![Graph API Explorer url](../images/developer-explorer.png)

5. click on the Application dropdown on the upper right part of the page. Select the application you just created.

![Graph API Explorer url](../images/graph-api-explorer-outline.png)

6. After selecting your application, click on the Get Token dropdown right below the Appliction dropdown and select Get User Access Token. It might open up a new window. **If it doesn't please check that popup blocker isn't active.**

![Get Token Dropdown](../images/get-token-dropdown.png)

7. In that window, select manage_pages and pages_show_list, then click Get Access Token

![Select Permissions Window](../images/select-permissions-window.png)

8. Click on the blue icon to the right most side of the Access Token input box.

![Blue Icon Outline](../images/graph-api-explorer-blue-outline.png)

9. A box should pop-up. In the box, click on Open in Access Token Tool. This will open up a new tab.

![Access Token Info Dropdown](../images/access-token-dropdown.png)

10. In the new tab, click on Extend Access Token.

![Extend Access Token Outline](../images/extend-access-token-outline.png)

11. A new box should show up, there click on the Debug button. This will open another new Tab.

![Debug Button and Key](../images/debug-button.png)

12. Go back to the first tab (Graph API Explorer) and replace the access token with the one from the last tab that was opened

![Replace Key](../images/replaced-key-access-token.png)

13. Change ```me?fields=id,name``` to ```me/accounts``` and click submit

![Change to ME/Accounts](../images/me-accounts.png)

14. Once done copy and paste the debug information to the email or support ticket

<!-- ## Delete Apps

1. If you need to delete an App please go  -->