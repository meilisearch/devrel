# New MeiliSearch releases - what to do

Those are the steps we need to take every time we release a new version of MeiliSearch.

## Table of Content
- [Responsibilities](#responsibilities)
- [Immediately after a release](#immediately-after-a-release)
- [Pre-release week](#pre-release-week)
- [Release day](#release-day)

## Responsibilities

Right now, unless mentioned, the tasks for a new release on the developer relations side are divided in three categories or actions with each person accountable for them:
- Documentation: [@react-learner](https://github.com/react-learner)
- Blog posts: [@CaroFG](https://github.com/CaroFG)
- Social media: [@fharper](https://github.com/fharper)

## Immediately after a release

Start of the monthly release cycle

1. Create a draft  on a branch called `prepare-meilisearch-[YYYY]-[WW]` (e.g.: prepare-meilisearch-2020-W3 for the third week of the year 2020) in the [documentation repository](https://github.com/meilisearch/documentation).
2. Add every PR from the corresponding [MeiliSearch Milestone](https://github.com/meilisearch/MeiliSearch/milestones) to the body of the `prepare-meilisearch-[YYYY]-[WW]` PR, with empty checkboxes next to each.
3. Strikeought the PR that don't need documentation modification.
4. Check the corresponding box once the relevant documentation has been added.
5. The documentation should contain at minimum references for the new feature(s), if any.
6. A decision should be made if we need to create a [guide](https://docs.meilisearch.com/guides/) for the new feature(s), if any.

## Pre-release week

 4th week of the monthly cycle

1. If the release has substantial new features, we should draft a [blog](https://blog.meilisearch.com/) post about the new release.
  - be clear about the new feature(s) and the impact on the users, if any
  - for API, add code example on how to use it
  - highlight breaking changes, if any
  - call to action, if any
2. he `prepare-meilisearch-[YYYY]-[WW]` PR should be reviewed and ready to merge to the primary branch (as of 2021, this is the [master branch](https://github.com/meilisearch/documentation/tree/master)).

## Release day

1. The `prepare-meilisearch-[YYYY]-[WW]` branch should be merged with the [master branch](https://github.com/meilisearch/documentation/tree/master). The updated version of the documentation should be [automatically deployed](https://docs.meilisearch.com/) momentarily.
2. Once the new documentation version is deployed, we should publish the blog post, if any.

_For the next steps, we will share the blog post; if none, we will share the [release notes](https://github.com/meilisearch/MeiliSearch/releases) from GitHub._

3. Share in the #general channel of our [Slack community](https://slack.meilisearch.com/) as yourself;
4. Share on [GitHub Discussions](https://github.com/meilisearch/MeiliSearch/discussions) as yourself;
5. Share on [Twitter](https://twitter.com/meilisearch) (from Mention);

_If the release contains enough interesting new features, we should:_

6. share on [LinkedIn](https://www.linkedin.com/company/meilisearch) (need to be admin of the LinkedIn page);
7. share on [Reddit](https://www.reddit.com/) (need to add the sub/subs) (credentials in 1Password);

_If the release is astonishing only, we should:_

8. share on [HackerNews](https://news.ycombinator.com/) as yourself.
