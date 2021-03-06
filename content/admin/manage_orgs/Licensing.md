<!--
title: "License Management"
description: "Overview of Licensing visibility"
tags: "Admin manage SuperAdmin EOP SaaS RASP IAST Licensing"
-->

Allocate, revoke and manage Assess and Protect licenses for individual organizations as a SuperAdmin. An Organization Admin may then apply and remove Protect licenses for servers in their organization. 

## Supervise Licenses

A SuperAdmin may grant separate Assess and Protect licenses to an organization in the **Organizations** page. (Assess licenses apply to applications and Protect licenses apply to servers.) The **Licenses** column in the organizations grid lists the number of used and unused licenses that have been granted. If licenses are nearing expiration, a red warning icon appears in the grid row. 

<a href="assets/images/Org-grid.png" rel="lightbox" title="Organizations page"><img class="thumbnail" src="assets/images/Org-grid.png"/></a>

### Allocate Licenses

To grant licenses to an organization, click the caret in the grid row and select **Allocate Licenses** from the row action dropdown menu. In the dialog that appears, SaaS users can enter the number of Assess and/or Protect licenses in the given fields to allocate to that organization. Click in the corresponding **Expiration Date** fields to make your selections on the calendars. EOP users can choose to allocate licenses from the total number available, which is shown in dialog along with the predetermined expiration dates. 

<a href="assets/images/Licenses-allocate.png" rel="lightbox" title="Allocate licenses dialog for SaaS"><img class="thumbnail" src="assets/images/Licenses-allocate.png"/></a>

### License Summary

You can manage the licenses granted to an organization by choosing **License Summary** in the row action dropdown menu, or by clicking on the license counts in the grid. The **License Summary** dialog provides thermometer charts of the organization's Assess and Protect licenses as well as upcoming expiration dates. SaaS users can use the links to **Allocate more licenses** or **Revoke unused licenses**. 

<a href="assets/images/License-summary.png" rel="lightbox" title="License Summary dialog for SaaS"><img class="thumbnail" src="assets/images/License-summary.png"/></a>

## Apply and Remove Licenses

An organization's administrator can apply, remove and view details on their Protect licenses in the **Servers** page grid.

### Apply licenses

To apply a Protect license to an an individual server, click the **UNLICENSED** link beside the server name, or click the caret in the grid row and choose **Apply Protect License** from the row action dropdown menu. To apply Protect licenses to multiple servers, select the checkboxes in the appropriate grid rows, click the shield icon in the batch actions menu above the grid, and choose **Apply Protect License** from the menu. Click the **Apply License** button in the confirmation dialog. 

Once a license is applied, the Protect toggle is enabled in the grid rows for the applicable servers.

<a href="assets/images/Servers-unlicensed.png" rel="lightbox" title="Apply a Protect license"><img class="thumbnail" src="assets/images/Servers-unlicensed.png"/></a>

>**Note:** Protect licenses are currently available for Java servers only.

#### Available licenses

If your organization has consumed all allocated licenses, or if the organization doesn't have enough licenses available for the number of servers selected, the option to apply a license is disabled. Hover over the disabled selection to **Apply Protect Licenses** for more information. 

> **Note:** To return a license to the pool of available licenses for the organization, you must remove it from a server. 

### Remove licenses 

To remove licenses from an individual server, click the caret in the grid row and choose **Remove Protect License** from the row action dropdown menu. To remove Protect licenses from multiple servers, select the checkboxes in the appropriate grid rows, click the badge icon in the batch action menu above the grid, and choose **Remove Protect License** from the menu. Click the **Remove** button in the confirmation dialog. 

<a href="assets/images/Servers-remove-license.png" rel="lightbox" title="Remove Protect license"><img class="thumbnail" src="assets/images/Servers-remove-license.png"/></a>

> **Note:** All licenses that you remove immediately return to the pool of available licenses for the organization. 



