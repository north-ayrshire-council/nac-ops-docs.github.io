!!! note
    Just test MD content to test POC - cheers Ross
# Contributing and Collaborating

This document is a set of guidelines for contributing and collaborating using Git and Gitlab. These are proposed guidelines, not rules. This guide is designed to make it easy for us all to collaborate together consistently and it is up for wider discussion.

## Script/Code Development

NAC OPs going forward will use [Git](https://git-scm.com/) as our [version control system](https://en.wikipedia.org/wiki/Version_control). We will develop new features, update scripts, fix bugs in separate Git branches, raise [Merge Requests](https://docs.gitlab.com/ee/user/project/merge_requests), assign them to a repo owner for review, and the owner will merge to `main` only after they are happy with the proposed update. 

We do not commit directly to the `main` branch.

Useful Git basics:

- [Getting Started Git basics](https://git-scm.com/book/en/v1/Getting-Started-Git-Basics) for Git beginners

### Commits

Please use detailed explanatory text in commit messages:

* If it is related to a Samanage Service Request or Incident, please include the case number; 
* If it fixes a bug, please state this and the bug it fixes;
* If it is a new feature, briefly describe the new feature.

A good commit message will help the whole team, so please make it clear and meaningful.

### Branches

There are a few ways to crack this nut and people can get passionate about each method, [this post covers them at a high level](https://medium.com/@patrickporto/4-branching-workflows-for-git-30d0aaee7bf). 

My vote would go for the Github Flow model.

### Merge Requests

If you are new to creating Merge Requests, click [here](https://docs.gitlab.com/ee/user/project/merge_requests/creating_merge_requests.html) for an easy-to-follow guide.

If you are still working on your merge request and are not yet ready for it to be reviewed and merged, then please start the title with `WIP:` to prevent a Work-In-Progress merge request from being merged before it is ready.

The Assignee should be one of the repo owners, which should be clearly outlined in the repo README. If you no longer require your branch after a merge to main (and you probably don't) please select the option to `Delete source branch when merge request is accepted`; this keeps the repo branches nice and tidy.

Merge Requests should strive to tackle one issue/feature and commits within this should try to "tell a story", making reviewing easier and faster.


#TBC

### Notifications

Repos should have notifications enabled via webhooks or email to ensure teams have visibilty on the progress/modifications of projects. 

Considerations when using notifications
1. Only useful notifications (Keep noise to a minimum)
2. Send to relevant channel(s)
3. ..... add as required
