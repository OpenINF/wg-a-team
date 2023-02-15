<!-- Begin GitHub-Flavored Markdown (GFM)
See: https://docs.github.com/get-started/writing-on-github
Spec: https://github.github.com/gfm
-->

<!-- Homepage modeled after https://wiki.mozilla.org/EngineeringProductivity -->

> **Note**: 
> As of 2023/02/14, the Engineering Productivity group, a.k.a. the A-Team, is
> no longer a discrete team. Its operations are split between the new Product
> Integrity WG meta-team and Engineering Operations. For now, many discussions
> around the test and automation work that was formerly under Engineering
> Productivity may continue in Matrix channels.

# The Engineering Productivity Team

Welcome to the homepage of the Engineering Productivity group (called “the A-Team”
for nostalgic reasons). Although formerly known as the Automation and Tools team,
we sometimes still use the nickname “A-Team”, and you'll see A-Team references
scattered around our codebases.

We're a group of programmers who develop and support a wide range of services,
tools, and automation that serve the engineering teams at OpenINF, with a
specific focus on work that increases the productivity of those teams. We are
part of the [Release and Productivity meta-team][].

## Our Mission

The Engineering Productivity Team is a Swiss Army Knife of coders dedicated
to improving the quality and productivity of engineering at OpenINF. Working
with others in a responsive and agile manner, we strive to be a model of open
development. We create, maintain, and extend a diverse array of sustainable
tools and systems that make and deliver information on the quality of OpenINF’s
products and enhance the impact and effectiveness of the OpenINF community.

## Connecting with the Team

We’re a friendly bunch of people who are happy to help you; we want to hear
about your ideas and your problems and what you think we could do to make your
work more productive.

See our Team Roster below for a list of folks on the team.

<!--
`ncu-team sync` updates the special "ncu-team-sync.team($org/$team)" comment
blocks with a list of members under the specified team.

Refs: https://nodejs.github.io/node-core-utils/docs/ncu-team.html#synchronize-files-with-special-blocks
-->

### Collaborators in the A-Team

<!-- ncu-team-sync.team(OpenINF/wg-a-team) -->

<!-- ncu-team-sync end -->

### Bots in the [**@OpenINF**][] Org

<!-- ncu-team-sync.team(OpenINF/bots) -->

<!-- ncu-team-sync end -->

<!-- Many of us blog about the things we work on; you can check
[our team planet](http://planet.mozilla.org/ateam/) for a feed of these. -->

## What We Work On

We work on a range of things that will vary from quarter to quarter, but the
lists below represent the general scope of our activities.

<!-- (!) NOTE: These may need to be replaced.

- **Services:** Bugzilla, MozReview, Autoland, Treeherder/Perfherder,
  OrangeFactor, hg.mozilla.org, git.mozilla.org, Pulse, ActiveData, Bugzilla ES,
  TestInformant, sheriffing of the tree
- **Automation:** Marionette, mochitest, xpcshell, reftest, web-platform-tests,
  Talos, MozBench, Robocop, Autophone, Bughunter, media and update tests for
  Firefox, GoFaster, CI integration (buildbot/TaskCluster), W3C WebDriver
  Specification, new test harnesses as needed
- **Tools:** mach, mozbase, mozregression, mozdownload, mozharness, mozci, SETA,
  code coverage
-->

## What We Don't Work On

We don't own [asbuild][], [TaskCluster][], or [depot_tools][] (those belong to
[our Release Engineering team][], [the Mozilla TaskCluster team][], and few
select [owners in the Chromium project][], respectively), although we
occasionally help with those projects as well.

> **Warning**: We don't write unit tests run in the test harnesses we own;
> developers are best suited and responsible for that.

We generally don't write functional tests run in the harnesses we own, although
we may help out here from time to time, mainly when this is done in conjunction
with developing a new harness. Our interests here are empowering developers to
write their own tests, but we sometimes contribute tests here as part of the
bootstrapping process. Ultimately, as with unit tests, developers are best
suited to writing functional tests and understanding overall test coverage and
design.

## Meetings

We have a fortnightly meeting every other Tuesday at 12am US Pacific Time. We
typically discuss status, and new projects, have demonstrations of the latest
tools & features, and sometimes even engage in bikeshedding. All are welcome;
please join us!

## Goals and Projects

We set and deliver quarterly goals, which is usually an excellent place to see
what we're up to. If you’d like us to incorporate some work into our plans, fill
out our project request form.

For a list of projects that we own, see Project Central.

Periodic team updates are posted to the \*-tooling mailing list.

## Getting Involved

We love contributors! We see community members as one of the keys to our success
and actively encourage and mentor their contributions. Working on the tooling,
automation, testing, and build systems at OpenINF is a fantastic introduction to
OpenINF development. There are two great ways to help: joining an existing
project or taking on one of our _starter_ projects to help you learn your way
around.

- [A-team bootcamp][]&#xFF1A;This covers the
  basics of getting started as an A-Team contributor
- [Quarter of Contribution][]&#xFF1A;Longer-running, scoped contributing
  opportunities with definite goals, mentors, and timelines
- [Existing Project][]&#xFF1A;Look over our
  [projects][] list and see if there is anything that you'd
  like to help with
- Good First Issues&#xFF1A;want a bug to try out? Find a few
  issues labeled https://github.com/OpenINF/.github/labels/help%20wanted or
  https://github.com/OpenINF/.github/labels/good%20first%20issue have been
  identified as desirable for community contribution. Feel free to work on
  <abbr title="Good First Issues">GFIs</abbr> even if not your first issue.
  - List of [all issues labeled _good first issue_][i-gfi]
  - List of [all issues labeled _help wanted_][i-help]
  - List of [all incomplete pull requests labeled _help wanted_][pr-help]
- Check out the [skills and areas][] of the team to see how you can fit in
  and help out!

If you have questions or want to sign up, please find us on Matrix.

[**@OpenINF**]: https://github.com/OpenINF
[i-gfi]:
	https://github.com/search?q=org%3Aopeninf+is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22
[i-help]:
	https://github.com/search?q=org%3Aopeninf+is%3Aissue+is%3Aopen+label%3A%22help+wanted%22
[pr-help]:
	https://github.com/search?q=org%3Aopeninf+is%3Apr+is%3Aopen+label%3A%22help+wanted%22
[pull request]:
  https://help.github.com/en/desktop/contributing-to-projects/creating-a-pull-request
[A-team bootcamp]: https://ateam-bootcamp.readthedocs.io/en/latest/
[Existing Project]: https://github.com/OpenINF/wg-a-team/wiki/Projects
[Quarter of Contribution]:
	https://github.com/OpenINF/wg-a-team/wiki/Auto-tools#quarter-of-contribution
[skills and areas]: https://github.com/OpenINF/wg-a-team/wiki/Auto-tools#skills-and-areas
