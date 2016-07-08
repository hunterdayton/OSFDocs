**Purpose:** The login form allows a user to access their existing OSF account.

When signed out, users can login by clicking the “sign in” button at the top right of the page in the :ref:`navigation bar <navigation-bar>`.
Clicking this button opens the CAS login page with fields for the login email and password. Below the submit (reads “Sign In”)
button, is a link that reads “Forgot Your Password?” Below this are links that read "Login Through Your Institution", "Back to OSF", and "Create Account". A box labeled "Stay Signed In" allows the user
to save their form input so that it appears the next time they visit this page.

If the user tries to login but enters an unregistered email or an incorrect password, an inline red alert below the password field reads::

    The email or password you entered is incorrect.

If a logged out user tries to access a :ref:`private <privacy>` OSF project, they are brought to the CAS login page (accounts.osf.io/login).


If the user tries to log in—on the login page—with a registered (primary or alternate) email and the right password,
they are brought to their dashboard. No alert is shown.

If the user tries to log in—on the login page—with a registered (primary or alternate) email with the wrong password,
an inline red alert is shown on the page. The user is told::

    The email or password you entered is incorrect.

No email is sent.

If the user tries to log in—on the login page—with an unregistered email, an inline red alert is shown on the page. The user is told::

    The email or password you entered is incorrect.

No email is sent.

If the user tries to log in—on the login page—with a deactivated email, they are brought to a page that says in red::

    This account has been disabled. Please contact support@osf.io to regain access.

No email is sent.

If the user tries to log in—on the login page—with an alternate email that has been removed, an inline red alert is shown
on the page. The user is told::

    The email or password you entered is incorrect.

No email is sent.

If the user tries to log in—on the login page—with a deactivated email with the wrong password, an inline red alert is
shown on the page. The user is told::

    The email or password you entered is incorrect.

No email is sent.

Logging in with Two-factor Authentication
------------

**Purpose:** Two-factor authentication provides added security to the user. It requires one additional step to ensure that
the user logging in is, in fact, the account holder.

To log in with two-factor authentication enabled, the user enters their email and password into the empty fields on the
login screen or from the navigation bar. After submitting, the user is asked for a two-factor authentication passcode.
The passcode is accessible via the authenticator (likely `Google Authenticator <https://support.google.com/accounts/answer/1066447?hl=en>`_)
app on their mobile device. Entering the passcode and clicking “Verify” or pressing the return key brings the user to their dashboard.

If the user submits a blank form, a red inline error is shown below the empty passcode field::

    Passcode is a required field.

If the passcode the user enters is incorrect, a red inline error is shown below the empty passcode field::

    The passcode you entered is incorrect.
