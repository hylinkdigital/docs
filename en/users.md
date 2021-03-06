Users
=====

Craft calls all member accounts of the system “users”.

The first user account is created during [installation]({entry:docs/installing:url}). If you stick with Craft Personal, this is the only account you will be able to create. If you need more, you will need to [upgrade](/pricing) to either Craft Client or Craft Pro, which offer additional user accounts.

## Admin Accounts

Admin accounts are special accounts that can do absolutely everything within Craft, including some things that there aren’t even explicit permissions for:

* Everything within the Settings section
* Make other users Admins (Craft Pro only)
* Administrate other Admins (Craft Pro only)

The user account you create during installation is an admin by default.

> Considering the amount of damage an admin can do, it’s strongly recommended that you be conservative with creating new admin accounts. Only do it if you trust that they know what they’re doing.

## Client’s Account

Craft Client allows you to add one additional user account to the system: the “Client’s Account”. You can create the Client’s Account via the Account menu in the top-right of the Control Panel:

The first time you click that option, you will be taken to a registration page where you can create the Client’s Account. Once it’s been created, it will take you to their account settings page instead.

The Client’s Account is _not_ an Admin account like yours, so they will not be able to access the Settings section or administrate your Admin account. They’ll be able to do everything else, though.

If you ever upgrade from Craft Client to Craft Pro, note that the Client’s Account will become just like any other user account. You will need to manually assign any permissions you want that account to have at that point.

## User Groups

If you have Craft Pro, you can create User Groups to help organize your site’s user accounts, as well as batch-set permissions on them.

To create a new User Group, go to Settings → Users and click the “New Group” button. You can give your group a Name and Handle, plus any permissions you want every user within the group to have.

Once your groups have been created, you can assign users to groups by going into their account settings and clicking on the Permissions tab.

## Permissions

Craft Pro allows you to set permissions on users and groups, such as the ability to access the control panel, edit content within certain sections, etc. They can be applied directly to user accounts as well as to user groups. When permissions are applied to a user group, all users that belong to that group will inherit them.

The permissions Craft comes with are:

{entry:snippets/user-permissions:body}

## Public Registration

Craft Pro has the option of allowing public user registration. It is not enabled by default, though. To enable it, you must go to Settings → Users → Settings, and check the “Allow public registration?” setting. With that checked, you will also be given the ability to choose a default user group that publicly-registered users are assigned to.

Once your site is set up to allow public user registration, the last step is to create a [user registration form]({entry:templating/user-registration-form}) on your site’s front end.
