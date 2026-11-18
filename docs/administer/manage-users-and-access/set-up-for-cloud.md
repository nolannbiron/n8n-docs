---
description: Set up user management on n8n Cloud
contentType: howto
nodeTitle: Set up for Cloud
originalFilePath: user-management/cloud-setup.md
originalUrl: 'https://docs.n8n.io/user-management/cloud-setup'
url: 'https://docs.n8n.io/administer/manage-users-and-access/set-up-for-cloud'
layout:
  description:
    visible: false
---

# Set up user management on n8n Cloud <a href="#set-up-user-management-on-n8n-cloud" id="set-up-user-management-on-n8n-cloud"></a>

{% hint style="info" %}
**Feature availability**

User management is available from n8n 0.195.0.
{% endhint %}

{% hint style="warning" %}
**Irreversible upgrade**

Once you upgrade your Cloud instance to an n8n version with user management, you can't downgrade your version.
{% endhint %}

## Step one: In-app setup <a href="#step-one-in-app-setup" id="step-one-in-app-setup"></a>

When you set up user management for the first time, you create an owner account.

1. Open n8n. The app displays a signup screen.
2. Enter your details. Your password must be at least eight characters, including at least one number and one capital letter.
3. Click **Next**. n8n logs you in with your new owner account.

## Step two: Invite users <a href="#step-two-invite-users" id="step-two-invite-users"></a>

You can now invite other people to your n8n instance.

1. Sign in to your n8n instance with your owner account. On n8n Cloud, if you're in the n8n Cloud console, select **Open instance** on the **Overview** page.
2. Select **Instance settings** at the bottom of the left menu.
3. Select **Users** to go to the **Users** page.
4. Select **Invite**.
5. Enter the new user's email address.
6. Select **Invite user**. n8n sends an email with a link for the new user to join.

## Related resources

* [Manage users and access](./)
* [Add and remove users](add-and-remove-users.md)
* [Understand instance roles](understand-instance-roles.md)
* [Set permissions and roles (RBAC)](set-permissions-and-roles-rbac/README.md)
* [Verify user identity](verify-user-identity/README.md)
* [Follow best practices](follow-best-practices.md)
