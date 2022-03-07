# Context
We want to establish the editorial **process** for taking **a blog post** (or an article that could be published elsewhere) from draft to publication.

# Tools
We'll follow the progress of a post from the idea to publication with [this table](https://github.com/meilisearch/devrel/blob/main/communication/post_forecast.md).

# Process
Here are the main stages to respect:

1. A Meilisearch member or an external contributor decides to write a post.

**Action for the author**:  Create a new row in the [post forecast table in this repo](https://github.com/meilisearch/devrel/blob/main/communication/post_forecast.md) with the following field values:
- **Topic**: the topic of your post
- **Link**: a link to the post being written (any platform is ok: Notion, HackMD, Google docs
- **Your name**: select your name
- **Your team**: select your team
- **Medium**: describe where your post should be published (sometimes it's not the blog)
- **Status**: `not started`.
- **ETA**: estimated date for publishing your post

2. The author writes the post.

**Action for the author**:  Change **Status** to `writing in progress`.

3. The author has finished the first draft of the post. The post is ready for review by the editorial committee or any other required feedback on the content.

**Action for the author**:  Change **Status** to `review needed`.

4. The author has a draft ready for proofread by the Meilisearch's documentation team.

**Action for the author**:  Change **Status** to `proofreading needed`.

5. Meilisearch's documentation team is currently proofreading the post.

**Action for the documentation team**:  Change **Status** to `proofreading in progress`.

6. Meilisearch's documentation team has finished proofreading the post.

**Action for the documentation team**:  Change **Status** to `proofreading finished`.

7. The author reviews the suggestions made by the proofreaders. The author repeats steps 5 and 6 until the post is ready for publication

**Action for the author**:  Change **Status** to `ready for publication`.

8. Meilisearch's team take care of the Publication if the medium is owned by Meilisearch, otherwise the author takes care of getting the post published.

**Action for the author**: 
- Change **Status** to `published`.
- Follow the process to indicate what info are in the post for maintenance reasons. See #348 


