# New MeiliSearch releases - what to do

Those are the steps we need to take every time we release a new version of MeiliSearch.

## Responsibilities

Right now, unless mentioned otherwise, the tasks for a new release on the developer relations side are divided into three categories or actions with each person accountable for them:
- Documentation & guides: [@react-learner](https://github.com/react-learner)
- Blog posts: [@CaroFG](https://github.com/CaroFG)
- Social media: [@fharper](https://github.com/fharper)

## After the last release

1. Create a PR on a branch called prepare-meilisearch-[YYYY]-[WW] (i.e.: prepare-meilisearch-2020-03 for the third week of the year 2020) in the [documentation repository](https://github.com/meilisearch/documentation).
1. Add every PR from the MeiliSearch Milestone in the prepare-meilisearch-[YYYY]-[WW] body with checkboxes.
1. Strikeought the PR that don't need documentation modification.
1. Check PR boxes when the documentation adding the related information is created.
1. The documentation must contain at minimum the references of the new feature(s), if any.
1. The decision should be made if we need to create a [guide](https://docs.meilisearch.com/guides/) for the new feature(s), if any.

## Pre-release week

1. If the release has substantial new features, we should draft a [blog](https://blog.meilisearch.com/) post about the new release.
  * be clear about the new feature(s) and the impact on the users, if any
  * for API, add code example on how to use it
  * highlight breaking changes, if any
  * call to action, if any
1. The prepare-meilisearch-[YYYY]-[WW] should be reviewed and ready to merge to the [master branch](https://github.com/meilisearch/documentation/tree/master).

## Release day

1. The prepare-meilisearch-[YYYY]-[WW] branch should be merged with the [master branch](https://github.com/meilisearch/documentation/tree/master), and updated version of the documentation published [in production](https://docs.meilisearch.com/).
1. Once in production, we should publish the blog post, if any.

_For the next steps, we will share the blog post: if none, we will share the [release notes](https://github.com/meilisearch/MeiliSearch/releases) from GitHub._

3. Share in the #general channel of our [Slack community](https://slack.meilisearch.com/) as yourself;
1. Share on [GitHub Discussions](https://github.com/meilisearch/MeiliSearch/discussions) as yourself;
1. Share on [Twitter](https://twitter.com/meilisearch) (from Mention);

_If the release contains enough interesting new features, we should:_

6. share on [LinkedIn](https://www.linkedin.com/company/meilisearch) (need to be admin of the LinkedIn page);
1. share on [Reddit](https://www.reddit.com/) (need to add the sub/subs) (credentials in 1Password);

_If the release is astonishing only, we should:_

8. share on [HackerNews](https://news.ycombinator.com/) as yourself.
