---
layout: default
title: Additional Information
permalink: priv-mgmt/more-info
collection: priv-mgmt
---

#### How do I find privileged accounts?
<b> By Name: </b> Your agency may have a naming convention for its accounts to identify privileged users. For example, some names may have -admin or -domainadmin as part of their usernames (jdoe-admin). This shouldn’t be the only way to find administrators since access can change over time.

<b> By Privileges:</b> Privileged network accounts have elevated access rights, typically in Active Directory, accounts are added to groups. Look through Active Directory to identify the groups that grant elevated permissions.

<b> By Inspection: </b> Occasionally, accounts are assigned elevated privileges individually. You will need to know your user population and find the edge cases.

Take care to remove duplicate accounts from the results! These metrics are counting unique accounts and users. For more information on Levels of Assurance, refer to [NIST SP 800-63-2](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63-2.pdf).

#### Examples:
For most agencies, network accounts are managed in Active Directory. Examples of shared accounts are accounts used for helpdesk, test, and training or guest accounts.