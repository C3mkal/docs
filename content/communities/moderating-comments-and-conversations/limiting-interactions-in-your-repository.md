---
title: Limiting interactions in your repository
intro: You can temporarily enforce a period of limited activity for certain users on a public repository.
redirect_from:
  - /articles/limiting-interactions-with-your-repository
  - /articles/limiting-interactions-in-your-repository
  - /github/building-a-strong-community/limiting-interactions-in-your-repository
versions:
  fpt: '*'
  ghec: '*'
permissions: People with admin permissions to a repository, and organization moderators, can temporarily limit interactions in that repository.
topics:
  - Community
shortTitle: Limit interactions in repo
---

## About temporary interaction limits

{% data reusables.community.interaction-limits-restrictions %}

{% data reusables.community.interaction-limits-duration %} After the duration of your limit passes, users can resume normal activity in your repository.

{% data reusables.community.types-of-interaction-limits %}

You can also enable activity limitations on all repositories owned by your user account or an organization. If a user-wide or organization-wide limit is enabled, you can't limit activity for individual repositories owned by the account. For more information, see "[Limiting interactions for your user account](/communities/moderating-comments-and-conversations/limiting-interactions-for-your-user-account)" and "[Limiting interactions in your organization](/communities/moderating-comments-and-conversations/limiting-interactions-in-your-organization)."

## Limiting interactions in your repository

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
1. In the sidebar, select **{% octicon "comment-discussion" aria-label="The comment-discussion icon" %} Moderation options**, then click **Interaction limits**.
{% data reusables.community.set-interaction-limit %}
  ![Temporary interaction limit options](/assets/images/help/repository/temporary-interaction-limits-options.png)

## Further reading
- "[Reporting abuse or spam](/communities/maintaining-your-safety-on-github/reporting-abuse-or-spam)"
- "[Managing an individual's access to an organization repository](/articles/managing-an-individual-s-access-to-an-organization-repository)"
- "[Permission levels for a user account repository](/articles/permission-levels-for-a-user-account-repository)"
- "[Repository roles for an organization](/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization)"
- "[Managing moderators in your organization](/organizations/managing-peoples-access-to-your-organization-with-roles/managing-moderators-in-your-organization)"