# Blog post process

## Context

We want to establish the editorial **process** for taking **a blog post** (or any content piece that could be published elsewhere) from draft to publication.

This content will go through an expert review from Meilisearch team members and through an editorial review from the documentation team.


⚠️ Posts that have a **hard publication deadline** (likely to be business-related) will be distinguished from other posts with a 🚨 in their estimated publication date. In this case, it's a hard deadline rather than an expected publication date.

## Tools

We'll follow the progress of a post from the idea to publication with [this table](https://github.com/meilisearch/devrel/blob/main/communication/post_forecast.md).

## Process

| Stage | Stage description | Action for the author | Action for the documentation team |
|---|---|---|---|
| 1 | A Meilisearch member or an external contributor decides to write a post. | The author has to create a new row in the [post forecast table](https://github.com/meilisearch/devrel/blob/main/communication/post_forecast.md) in this repo with the following field values:<br>- **Topic/title**: the topic or title of the content piece<br>- **Link**: a link to the post being written (any platform is ok: Notion, HackMD, Google docs)<br>- **Author**: the author name<br>- **Medium**: mediums where the post should be published (sometimes it's not the blog)<br>- **Status**: `not started`.<br>- **ETA**: tentative publication date. If this date is a hard deadline, precede it with a 🚨 |  |
| 2 | The author writes the post. We advise the use of a [writing assistant](https://github.com/meilisearch/devrel/blob/main/process/blog_process.md#tools).| Change **Status** to `writing in progress` |  |
| 3 | The author has finished the first draft of the post.<br>The post is ready for review by the expert committee or any other required feedback on the content (e.g., a team manager). | Change **Status** to `expert review needed` |  |
| 4 | The expert committee is currently reviewing the post. The author may update the content accordingly in this stage and require other expert reviews. | Change **Status** to `expert review in progress` |  |
| 5 | The author has a draft ready for editorial review by Meilisearch's documentation team. | Change **Status** to `editorial review needed` |  |
| 6 | Meilisearch's documentation team is currently reviewing the post. |  | Change **Status** to `editorial review in progress` |
| 7 | Meilisearch's documentation team has finished reviewing the post. |  | Change **Status** to `editorial review finished` |
| 8 | The author reviews the suggestions made by the proofreaders.<br>The author repeats steps 5 to 7 until the post is ready for publication. | Change **Status** to `ready for publication` |  |
| 9 | Meilisearch's DevRel team takes care of the publication if Meilisearch owns the medium,<br>otherwise, the author takes care of getting the post published. | - Change **Status** to `published`.<br>- Follow the process to indicate what info is in the post for maintenance reasons. See [#348](https://github.com/meilisearch/devrel/issues/348) |  |

## Process compliance failure

### ETA update

If the ETA is modified (this can be a delay or adding a heard deadline), the group responsible for the ETA update (this can be the author during stages 1 to 4 and 8 to 9, or the documentation team during stages 5 to 7) has to tag the other group and the DevRel team in the ETA update PR and make sure that they are aware of this change.
