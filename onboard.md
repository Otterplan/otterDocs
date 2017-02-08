# New Engineer Onboarding
Living document outlining Otterplan's engineering tools, standards, and documents.

## Tools

- [Zenhub](https://www.zenhub.com/) to manage epics and issues in Github.
- [Trello](https://www.trello.com/) to manage your and the team's high level (stakeholder
  communicable) tasks.
- [Slack](https://www.slack.com/) for async communication with teammates.
- Email for communicating with anyone not in Slack.
- [AWS](https://aws.amazon.com/) for managing our cloud infrastructure.


## Important Docs

- Leadly design sketch [file](https://www.dropbox.com/sh/fs1mvx38tsxthig/AAAwalIAA_TGyfCjduJpLxGxa?dl=0)


## Processes

### Contributing

You should:
  - Run tests and lints locally before pushing to a remote repository.
  - Use pull requests to contribute code to master.
  - Add any relevant peers as a 'Reviewer' of the PR.

You should not:
  - Push directly to master or prod.
  - Push code without working tests.

### Git Branch, Commit, PR messaging

You should:
  - Prepend your branch name with your initials (jm/onboarding-doc).
  - Squash PRs with a large number of commits.
  - Use descriptive commit messages and branch names.
  - Include a descriptive PR message for the reviewer

You should not:
  - Assume the reviewer has previous knowledge of the code you're pushing.
  - Assume the reviewer has time to decrypt your PR message into something that makes sense.

### Continuous Deployment/Integratin

We use [CircleCI](https://www.circleci.com) to manage integration and deployment.

### AWS Infrastructure

We use it.

### Releasing

You should:
  - Use [semver](http://semver.org/).
  - Use tag commits with the release version, ex 'v0.1.0'
  - Use Github's release feature to publish release notes

You should not:
  - Push to master or prod without a release tag.
  - Push to master or prod without bumping the version.

### Standups

You should:
  - Use trello to quickly communicate high level goals daily.
    - ex "James's Daily Priorities" - Inbox | Daily | Completed | Blocked
  - Don't be afraid to ask questions if you're blocked or stuck :)
  - Reflect on your estimation accuracy at regular intervals.

You should not:
  - Overestimate and have to rush to complete work with a lower quality.
  - Think you need to move lots of cards to look productive.


## Style Guides

TODO:
  - Link to Typescript style guide
  - Link to React style guide
  - Link to Python style guide
  - Add Tim's design style guide


## ETC

Don't forget the work/life balance :)



