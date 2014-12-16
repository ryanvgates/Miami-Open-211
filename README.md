Miami-Open-211
==============

Open 211 for Miami Dade County.

Project page: [http://projects.codeformiami.org/projects/miami_open211](http://projects.codeformiami.org/projects/miami_open211)

We're working with [Switchboard of Miami](http://switchboardmiami.org/) and the [Open Referral Initiative](https://www.openreferral.org/) to create Miami Open211: a platform for directory information about all of the health, human, and social services in our community.

Switchboard of Miami operates Miami-Dade's 2-1-1 call center, through which people in need can call to get referrals to services that can help them.

Switchboard has agreed (as an experiment) to deploy their data in an open platform that can be accessed by external tools and applications. (They'll be one of the first 2-1-1s in the country to do so!) [Read more about the Miami project here.](https://docs.google.com/document/d/1UclLolk4W1hoSo1BUY8Da9A_hO_hHM89vggJg6KfCOA/edit)

In the first phase of this project, we are going to experiment with the [Ohana API.](https://github.com/codeforamerica/ohana-api)

###Identified steps:

- Transform a demonstrating package of Switchboard's 2-1-1 data into the Open Referral format. [Github repo here](http://github.com/codeforamerica/OpenReferral) — [Updated spec documentation here](https://docs.google.com/document/d/1gmNS4pBvkX4cI2wtH3Qco3uGF4LLTq1OJ0Pb_CLuxlk/edit)(this will require some script-writing and munging)
- Deploy Ohana API (it's in Ruby on Rails)
- Load transformed 2-1-1 data into Ohana [Instructions here.](https://github.com/codeforamerica/ohana-api/wiki/Populating-the-Postgres-database-from-OpenReferral-compliant-CSV-files)
- Deploy the Ohana Web Search module, for a basic front-end to start us off.
- Celebrate victory!

Our Open Referral community is convened in this [Google Group.](http://groups.google.com/forum/#!forum/openreferral) It would be great to have at least one Code for Miami brigadeer join and introduce yourself and the project!

Background on Open Referral: The Open Referral Initiative is working to make it easier to share and find information about health, human, and social services. We are supporting local pilot projects in which diverse stakeholders are establishing interoperability between human service information systems (i.e., enabling different systems to ‘talk’ to each other). Our objective is to demonstrate the value of making resource data openly available in a standard format.
