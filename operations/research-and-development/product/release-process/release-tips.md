# Release Tips

**Changelog Checklist**

* Features
  * State benefits first.
  * Order features based on benefit for end users.
  * Include links to docs where appropriate.
* Bugs
  * Check/test if the issue was in previous server version.
* All sections
  * Check that all sections are written and formatted the same way as in previous changelogs.
* API/Websocket/Database
  * Work with Devs on this section.
* Next version
  * If the changelog mentions items regarding upcoming versions, move them to the bottom of the changelog.

**Ways to Meet Deadlines**

* Post a list of dates for next release at or soon after T-0 and ping all of the teams.
* For features and bugs, start pinging early enough before due dates and make public posts.
* When pinging people, provide a clear due date and give a reason for the due date \(e.g., Code Complete on Monday\).
* Ask if people need any help or have any questions.

**Translations**

* Monitor progress of translations at [https://translate.mattermost.com/](https://translate.mattermost.com/) and ping language maintainers a few days before due date if they're not getting to 100%.
* Ask DevOps to submit a new translations PR if a translation deadline extension is requested.
* Target date for final translations PR is T-5, but T-3 is acceptable.

**Ways That** [**Features/Bugs Guidelines**](https://docs.google.com/document/d/1QxB_A1qkEJBKAvQpRa7JiSQLZhwg6HAEajNRNa7ldGg/edit) **are Currently Enforced**

* Features guidelines:
  * Start to ping people already at T-15 or earlier for feature PRs that are still open.
* Bugs guidelines:
  * Need to focus on fixing only S1 and S2 bugs after T-5 to avoid missing T-2 deadline for cutting the final.

**Ways to Ensure Features are Tested for HA/Mobile/Scale**

* Mobile: Added a release checklist item for QAs for T-11.
* HA: Test server available.
* Scale: Via loadtests.

**Release Marketing**

* Blog post:
  * Follow [guidelines](https://handbook.mattermost.com/operations/messaging-and-math/how-to-guides-for-m-and-m/how-to-create-release-announcements).

