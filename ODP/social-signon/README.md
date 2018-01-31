# Social Sign-on Documentation

This repo is to outline the steps and processes to build in single sign-on to the [Democracy Kit](https://democracykit.org) website.

## Google

Follow the steps in [this guide](https://bootstrap.brilliantdirectories.com/support/solutions/articles/12000036962-google-login), with some modifications.

After step 18 where you enable the Google People API:

1. Go to the credentials and click on *Domain Verification*.
2. Click add a domain, and fill in the domain name.
3. You can try using their regular signon methods with your GoDaddy credentials (or other domain name service). If it doesn't validate your domain name then click on alternate methods.
4. Use the method where you add a meta tag to the home page. Copy and paste that meta tag.
5. Go back to the Brilliant Directories admin page, navigate to the sidebar *Content* and click *Edit Web Pages*.
6. Click the edit button on *Home Page*, scroll down to *Customize Page Level Head Tags* and click save.
7. Go back to the Google Developer Console and try to verify.
8. Now return to the rest of the steps in the initial steps outlined by Brillaint Directories.

## Facebook

Follow the steps in [this guide](https://bootstrap.brilliantdirectories.com/support/solutions/articles/12000036273-facebook-login), with some modifications.

After step 9 add this step:

1.Go to *Settings* and under *App Domains* fill in the domain for the website.

And do the rest of the steps and it should work!
