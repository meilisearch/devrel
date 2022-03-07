# Blog post process

## Context
We want to establish the editorial **process** for taking **a blog post** (or an article that could be published elsewhere) from draft to publication.

## Tools
We'll follow the progress of a post from the idea to publication with [this table](https://github.com/meilisearch/devrel/blob/main/communication/post_forecast.md).

## Process

| Stage | Stage description | Action for the author | Action for the documentation team |
|---|---|---|---|
| 1 | A Meilisearch member or an external contributor decides to write a post. | Create a new row in the [post forecast table in this repo](https://github.com/meilisearch/devrel/blob/main/communication/post_forecast.md) in this repo with the following field values:<br>- **Topic**: the topic of your post<br>- **Link**: a link to the post being written (any platform is ok: Notion, HackMD, Google docs<br>- **Your name**: select your name<br>- **Your team**: select your team<br>- **Medium**: describe where your post should be published (sometimes it's not the blog)<br>- **Status**: `not started`.<br>- **ETA**: estimated date for publishing your post |  |
| 2 | The author writes the post. | Change **Status** to `writing in progress` |  |
| 3 | The author has finished the first draft of the post.<br>The post is ready for review by the editorial committee or any other required feedback on the content. | Change **Status** to `review needed` |  |
| 4 | The author has a draft ready for proofread by the Meilisearch's documentation team. | Change **Status** to `proofreading needed` |  |
| 5 | Meilisearch's documentation team is currently proofreading the post. |  | Change **Status** to `proofreading in progress` |
| 6 | Meilisearch's documentation team has finished proofreading the post. |  | Change **Status** to `proofreading finished` |
| 7 | The author reviews the suggestions made by the proofreaders.<br>The author repeats steps 5 and 6 until the post is ready for publication. | Change **Status** to `ready for publication` |  |
| 8 | Meilisearch's team take care of the Publication if the medium is owned by Meilisearch,<br>otherwise, the author takes care of getting the post published. | - Change **Status** to `published`.<br>- Follow the process to indicate what info are in the post for maintenance reasons. See [#348](https://github.com/meilisearch/devrel/issues/348) |  |
