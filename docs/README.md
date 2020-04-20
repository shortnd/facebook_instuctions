# Facebook Token Instructions

## Create Apps and Tokens
Below are the instructions to create a facebook token for your page.

1. Login to Facebook using a Desktop Computer. **IMPORTANT:** Login using an account that has admin rights to the Facebook page your would like to pull posts from. Then go to [https://developers.facebook.com](https://developers.facebook.com)

![Facebook Developer Menu](../images/developer-facebook-menu.png)

2. Click on Add New App.

![Create App Link](../images/create-app-link.png)

3. Fill the Display Name and Contact Email and click Create App ID

![New App ID](../images/create-new-app-id.png)

4. After creating the application, go to [https://developers.facebook.com/tools/explorer](https://developers.facebook.com/tools/explorer).

![Graph API Explorer url](../images/developer-explorer.png)

5. Select your App from the drop down

![Select Facebook App](../images/facebook-select-app.png)

6. Then select "Get User Access Token" from the User or Page Select

![Select User or Page](../images/facebook-select-user-token.png)

- You will get a new window where it askes to verify if you want to continue with this account.

7. Under Permissions select the two options for manage_pages and pages_show_list

![Pages Permissions](../images/facebook-permissions.png)

8. Click Generate Access Token

![Facebook Access Token](../images/facebook-generate-access-token-button.png)

9. In the next popup, select "Continue as `<your account>`", then select the page you want to show. On the next option make sure all options are selected and click "Done". Once it finishes click "OK"

10. Click the blue "i" icon next to the access token

![Blue Access Token](../images/facebook-blue-access-token.png)

11. Then in the new popup select "Open in Access Token Tool"

![Open in Access Token Tool](../images/facebook-open-in-access-token-tool.png)

12. Once the new tab loads go down to the bottom and click "Extend Access Token"

![Extend Access Token Button](../images/facebook-extend-access-token-button.png)

13. Re-enter your password in the popup.

14. Then click the "Debug" button

![Debug button](../images/facebook-debug-button.png)

15. In the new tab select all the text in the box

![New Access Token Selected](../images/facebook-select-all-text.png)

16. Go back to the original tab "Graph API Explorer" and paste the copied text into the access token box

![Pasted in access token](../images/facebook-paste-access-token.png)

17. Change the ```me?fields=id,name``` to ```me/accounts``` then click submit

![Changed to me/accounts](../images/facebook-me-accounts.png)

18. Then click "Copy Debug Information" paste the debug information to the email or support ticket

![Copy Debug Information](../images/facebook-copy-debug-info.png)


## Delete Apps

1. If you need to delete an App, click on the My Apps Dropdown

![Outline of My Apps Dropdown](../images/my-apps-outline.png)

2. Click See All Apps Option

![Outline of See All Apps](../images/see-all-apps-outline.png)

3. Hover over the App you want to delete and click the down arrow that appears

![Selected app hover with down arrow](../images/hover-over-selected-app.png)

4. Click the delete app option

![Delete app dropdown](../images/delete-app.png)

5. In the popup click delete app

![Popup for Delete App](../images/delete-app-popup.png)

6. Then reenter your password and submit. Once submitted your app will be deleted.

![Enter your password to delete app](../images/enter-password.png)
