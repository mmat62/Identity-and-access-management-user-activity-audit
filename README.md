# Identity and Access Management: User Activity Audit

Investigate a security incident involving unauthorized access, review log and identify what happened to prevent any future incidents

## Context

Recently, a deposit was made from the business to an unknown bank account. The finance manager says they didn’t make a mistake. Fortunately, they were able to stop the payment. The owner has asked you to investigate what happened to prevent any future incidents.

## Access log review

### Event log

![image](https://raw.githubusercontent.com/mmat62/Identity-and-access-management-user-activity-audit/refs/heads/main/Event%20log.png)

- The event took place on 10/03/23.
- The user is Legal/Administrator.
- The IP address of the computer used to login is 152.207.255.255.

Event logs can often help identify the who, what, and why of a security incident.

## Identify access control issue(s):

### Employee directory

![image](https://raw.githubusercontent.com/mmat62/Identity-and-access-management-user-activity-audit/refs/heads/main/Employee%20Directory.png)

- Robert Taylor, Jr. is  a contractor with admin access.
- His contract ended in 2019, but his account accessed payroll systems in 2023.

Oftentimes, incidents like this occur because systems are misconfigured or misused. That is the case with how this business is sharing information among its employees.

## Recommended mitigations

- User accounts should expire after 30 days.
- Contractors should have limited access to business resources.
- Enable multi-factor authentication (MFA).

It appears as though a former employee is potentially the threat actor. However, it's possible that they were not the person responsible for this security incident.

It is common for people to reuse login credentials across many services. And if those credentials are compromised on one platform then an attacker can use them to gain access to others. In this case, implementing access controls, like password policies, limited file permissions, and MFA can protect the business from incidents like this.
