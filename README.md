## Steps to setup the project:

Switch to the specific branch and then read the README.MD file to run the code.

  Topic --> Branch Name
-------------------------------------------------------------
- Oauth2                      --> oauth2
- JWT                         --> jwt
- Oauth & Notification Module --> oauth2-notifications
- JWT & Notification module   --> jwt-notifications

### There are some other features also that you can use:

 - If you want to show the tool-tip error messages in web-admin panel,
   use the showError("error message") function in js.
 - If you want to show the tool-tip success messages in web-admin panel,
    use the showSuccess("success message") function in js.
 - There is a preLoaded confirmation-modal in the templates > common > confirmation-modal.html.
    just include that file in your html file and use it as follows:
    > $("#confirmation-modal-title").html("Logout");
    > $("#confirmation-modal-description").html("Are you sure want to logout?");
    > $("#confirmation-modal-yes-button").attr("onClick", "logout()");
    > $("#confirmation-modal-yes-button").html("Yes");
    > $("#confirmation-modal-no-button").html("Cancel");
    > $("#deactivate-customer").modal('show');
 - To show the loader, use showLoader();
 - To hide the loader, use hideLoader();
 - To hide the success/error tooltips, use preLoaded function timeOut();
 - The default timeout is 4500 you can change it in apps > web_admin > static > js > common.js > timeOut()
