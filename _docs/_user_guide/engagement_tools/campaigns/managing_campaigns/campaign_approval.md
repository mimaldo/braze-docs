---
nav_title: Approving Campaigns
article_title: Approving Campaigns
alias: "/campaign_approval/"
page_order: 0
page_type: reference
description: "This page provides an overview of the campaign approval process."
tool: Campaigns
---

# Approving campaigns

> Campaign approval adds a review process to your workflow before launching a campaign. Available exclusively for campaigns, this feature adds new states available in the campaign confirmation workflow step. Now, you can ensure that each confirmation is approved in order to launch the campaign.

{% alert important %}
Campaign approval is not supported in the building workflow for Canvases, API campaigns, and Transactional Email campaigns.
{% endalert %}

## Turning on campaign approval

By default, the campaign approval setting is turned off. To enable this feature, go to **Settings** > **Approval Workflow**.

{% alert note %}
If you are using the [older navigation]({{site.baseurl}}/navigation), you can find this page at **Manage Settings** > **Approval Workflow**.
{% endalert %}

## Using approvals

Before using the approval workflow, you must have the "Approve and Deny Campaigns" permission. This permission controls who can update the approval status of a campaign. This permission can also be applied to workspaces or [teams]({{site.baseurl}}/user_guide/administrative/app_settings/manage_your_braze_users/teams/), or added to a [permission set]({{site.baseurl}}/user_guide/administrative/app_settings/manage_your_braze_users/user_permissions/#permission-sets).

In the **Review Summary** step of the campaign building workflow, use the approval option to approve or deny your campaign's key components: **Messages**, **Delivery**, **Target Population**, and **Conversion Events**. The default state for campaign approval is **Pending Approval**. 

![][1]

Once each section is approved, the **Launch** button will be enabled and you can launch your campaign! 

[1]: {% image_buster /assets/img_archive/campaign_approval_example.png %} 
