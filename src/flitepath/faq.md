# FAQ

## How do I contact support if I have a problem?

If you are a Venture Hive customer then you automatically have support. There are no extra hoops to jump through. You may contact support at any time via the "Feedback & Support" tab found on the right side of the browser window or by email at `support@venturehive.com`.

## Can I suggest a feature? How long will it take to implement?

You may certainly suggest a feature whenever you like via the "Feedback & Support" tab found on the right side of the browser window or by email. We will deliberate, prioritize and implement accordingly, but we will always keep you "in the loop".

## Why did you build Flitepath from scratch?

Flitepath's predecessor was built on top of a CMS (Content Management System). We found several issues with that approach, though.
Namely: Lack of flexibility, slow performance, slower development cycles, and maintenance issues.

For our programs to run smoothly, we need a system that delivers all of the features enumerated below (amd more). We found that it was much easier and safer to get all of these features and more implemented and performing how we wanted them on our own than with a CMS.

1. Calendars
2. Self service venture promotion and venture profile maintenance
3. User and member management (both self service and admin managed)<br>
   a. Program level role definition and assignment<br>
   b. Venture associations (members, executives, admins, coaches)
4. Meeting management
5. Objective management
6. Event management
7. Venture management
8. Venture tracking<br>
   a. Quantitative measurement - Metrics<br>
   b. Qualtitative measurement - Meeting Notes<br>
   c. Be able to track pivots, etc
9. Manage Entrepreneur progress
10. Manage Content<br>
   a. Resources<br>
   b. Integrate with LMS<br>
   c. Expert system - TBD
11. Manage users at the network level (multiple VH locations)<br>
   a. Give users access to each other across network<br>
   b. Search by skills
12. Single Codebase for Venture Hive and Venture Hive U platforms<br>
   a. Configurable - Feature configuration per site<br>
   b. Customizable - Institutional identity, location, etc.<br>
   c. i18n - Different languages and formats
13. Reporting
14. Custom Notofications
15. Real time site level customizations
16. Clear and concise data schema
17. Easy integration with potentially various authentication servers

## What technology did you use to build Flitepath?

Flitepath is built using the [Grails](https://grails.org/ "Grails") web framework which takes advantage of the [Groovy](http://www.groovy-lang.org/ "Groovy") programming language.

## We have our own authentication server in place (Active Directory, LDAP, etc) and we want to use that instead of creating a new account in Flitepath. Is that possible?

We may be able to integrate your existing authentication server but we would need more specifics on your particular server type, authentication schema, access to your network, etc, to know for sure.

## Can Flitepath be deployed behind our firewall?

We haven't yet deployed flitepath on-site mainly because one of our features involves Venture Hive network-wide user search and centralized administration.

## Can we use our own subdomain/domain for our Flitepath site?

You can point your URL to your Flitepath site's URL using a CNAME DNS record, but we'll have to make a quick web server change to accomodate the new CNAME.
