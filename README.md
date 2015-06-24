IMPORTANT UPDATE
============================
Please update to [GAM 3.45] immediately. The latest available GAM version 3.45 contains critical modifications for password updates during user creation / update (gam create user and gam update user). Google has made server-side changes, requiring users to use 3.45 to ensure proper functionality. Please ensure that you update to [GAM 3.45] immediately. Failure to update may result in "Invalid Input" errors.

As a quick workaround instead of upgrading, you can add "nohash" to the user update/create command in order to workaround the issue. This will cause GAM to send the new user password in plaintext over the TLS HTTPS connection.

GAM
============================
GAM is a free, open source command line tool for
Google Apps Administrators to manage
domain and user settings quickly and easily. GAM supports

* creating, deleting, and updating users, aliases, groups, 
  organizations, and resource calendars
* modifying user email settings such as IMAP, signatures,
  vacation messages, profile sharing, email forwarding,
  send as address, labels, and features.
* modifying calendar access rights for users and resource calendars.
* generating detailed reports for users, groups, resources,
  account activity, email clients, and quotas.
* and many more commands

Downloads
---------
You can download the current GAM release from 
the [GitHub Releases] page.

Documentation
------------------
The GAM documentation is hosted in the [GitHub Wiki]

Mailing List / Discussion group
-------------------------------
The GAM mailing list / discussion group is hosted
on [Google Groups].  You can join the list and interact
via email, or just post from the web itself.

Source Repository
-----------------
The official GAM source repository is on [GitHub] in the master branch.

Author
------
GAM is maintained by <a href="mailto:jay0lee@gmail.com">Jay Lee</a>.

[GAM 3.45]: https://git.io/gamreleases
[GitHub Releases]: https://github.com/jay0lee/GAM/releases
[GitHub]: https://github.com/jay0lee/GAM/tree/master
[GitHub Wiki]: https://github.com/jay0lee/GAM/wiki/
[Google Groups]: http://groups.google.com/group/google-apps-manager
