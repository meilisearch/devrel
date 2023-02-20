# Posts editorial process

## Context

We want to establish the editorial **process** for taking **a blog post** (or any content piece that could be published elsewhere) from draft to publication.

This content will go through an expert review from Meilisearch team members and through an editorial review from the documentation team.


⚠️ Posts that have a **hard publication deadline** (likely to be business-related) will be distinguished from other posts with a 🚨 in their estimated publication date. In this case, it's a hard deadline rather than an expected publication date.

## Tools

We'll follow the progress of a post from the idea to publication with [this table](https://meilisearch.notion.site/Post-forecast-a5b3ede0ee744553bfa63810807ac507).

## Process

| Stage | Stage description | Action for the author | Action for the Documentation team |
|---|---|---|---|
| 1 | A Meilisearch member or an external contributor decides to write a post. | The author has to create a new row in the [post forecast table](https://www.notion.so/meilisearch/Post-forecast-a5b3ede0ee744553bfa63810807ac507) in Meilisearch's Notion workspace with the following field values:<br>- **Topic/title**: the topic or title of the content piece<br>- **Link**: a link to the post being written on **Google docs**. You can find a **blog post template** in the Template Gallery <br>- **Author**: the author's name<br>- **Medium**: mediums where the post should be published (sometimes it's not the blog)<br>- **Status**: `not started`.<br>- **Priority**: If this date is a hard deadline, select the `🚨 hard deadline` option <br>- **Publication date**: tentative publication date. <br>- If it's a blog post, add the desired [tag](https://github.com/meilisearch/devrel/blob/main/guidelines/tag_guidelines.md) in the 'Blog tag' column |  |
| 2 | The author writes the post. We advise the use of a [writing assistant](https://github.com/meilisearch/devrel/blob/main/process/blog_process.md#tools).| Change **Status** to `writing in progress` |  |
| 3 | The post's writing has been paused due to other priorities or is blocked by external factors. | - Change **Status** to `blocked/paused` <br> - If possible, provide relevant information about the pause/blockage in the 'Comments' column |  |
| 4 | The author has finished the first draft of the post.<br>The post is ready for review by the expert committee or any other required feedback on the content (e.g., a team manager). | Change **Status** to `expert review needed` |  |
| 5 | The expert committee is currently reviewing the post. The author may update the content accordingly in this stage and require other expert reviews. | Change **Status** to `expert review in progress` |  |
| 6 | The author has a draft ready for editorial review by Meilisearch's documentation team and tags the Documentation team (@meilisearch/docs-team). | Change **Status** to `editorial review needed` |  |
| 7 | Meilisearch's documentation team is currently reviewing the post. |  | - Change **Status** to `editorial review in progress` <br>- Add the reviewer's name to the **Reviewer** column  |
| 8 | Meilisearch's documentation team has finished reviewing the post and notify the author. |  | Change **Status** to `editorial review finished` |
| 9 | The author reviews the suggestions made by the proofreaders.  |The author repeats steps 5 to 7 if necessary. |  |
| 10 | The author follows the [blog publishing process](https://github.com/meilisearch/devrel/blob/main/process/blog_publishing_process.md) until the post is ready for publication.  | - Change **Status** to `ready for publication`|  |
| 11 | Meilisearch's DevRel team takes care of the publication if Meilisearch owns the medium,<br>otherwise, the author takes care of getting the post published. | - Update the **Link** field with the URL of the published post <br> - Change **Status** to `published` <br>- Follow the process to indicate what info is in the post for maintenance reasons. See [#348](https://github.com/meilisearch/devrel/issues/348) |  |

## Process compliance failure

### Publication date update

If the publication date is modified (this can be a delay or adding a heard deadline), the group responsible for the publication date update (this can be the author during stages 1 to 4 and 8 to 9, or the documentation team during stages 5 to 7) has to notify the other group and the DevRel team and make sure that they are aware of this change.
