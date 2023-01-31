# Blog publishing process

## Context
Once an article has been reviewed, authors need to follow the steps below to make sure their content is ready for publication.

## Process
1. Before publishing an article, you need access to [Ghost](https://meilisearch.ghost.io/ghost/)
    - Meilisearch workers: ask someone from the DevRel team to create credentials for you
    - External contributors: discuss this with your contact at Meilisearch
2. Make sure you have properly filled in your profile description. Check the [profile creation process](https://github.com/meilisearch/devrel/blob/main/process/blog_profile_creation.md) if needed.
3. Once you are connected to Ghost, you can click on `New Post` in the top right corner of the page. Upon clicking it, you are immediately taken to the Ghost editor page
4. Write the post title
5. Copy and paste the post content into the Ghost editor
6. Make sure no information was lost. It's important to check:
    - Links
    - Format: 
        - Headings
        - Font weight: bold, italics...
        - Spaces between paragraphs
        - Quotation marks! 
        - Code snippets ⚠️ Don't forget to choose the right programming language! 
        <img src="https://user-images.githubusercontent.com/48251481/176222665-682e125a-d1ab-4569-aa54-e49971000105.png" width="33%" style="float: right;">

        - Lists
        
   <img src="https://user-images.githubusercontent.com/48251481/172438035-e9a83413-b1c2-4539-8b8c-f36341344011.png" width="25%"> 👉 <img src="https://user-images.githubusercontent.com/48251481/172438051-21a6acc8-9a44-4214-b4d0-ff6b012f7a83.png" width="25%">

7. Insert the desired illustrations into the body (screenshots, etc.), please make sure they comply with [the size and quality requirements](https://github.com/meilisearch/devrel/issues/362).
    - Place the cursor where you want the image to be displayed (it has to be an empty line)
    - Click on the `+` button at the beginning of the line, and select the `Image option` in the dropdown menu
    
    <img src="https://user-images.githubusercontent.com/48251481/172434571-8afc1918-f358-4b79-99ed-bd9b67afa4dd.png" width="50%">

8. Add the cover image by clicking on `+ Add feature image` above the post title. Make sure it complies with the [blog cover guidelines](https://github.com/meilisearch/devrel/issues/383)

9. Add the alternative text of the images and a caption if necessary
<img src="https://user-images.githubusercontent.com/48251481/172434356-f0b28d79-cf09-4af7-a4ec-0e78b137b338.png" width="50%"> 

10. Open the `Post settings` by clicking on the icon next to the `Save` button at the top right corner of the page:
    - Add the Post URL. Make sure it complies with the [URL guidelines](https://github.com/meilisearch/devrel/blob/main/guidelines/url_guidelines.md)
    - Add the excerpt of the post: it is limited to 300 characters, but it is better to make it shorter. You can check the [excerpt guidelines](https://github.com/meilisearch/devrel/issues/453)
    
    <img src="https://user-images.githubusercontent.com/48251481/172436396-a3829311-92b5-49cf-bae5-6a777603a24c.png" width="25%">

11. Check the `Meta data` and the `Twitter card` and adapt the titles and descriptions if needed (avoid cropped text)
   <img src="https://user-images.githubusercontent.com/48251481/172437697-7ad3e248-6021-48a2-ba37-c3bf2f085b9f.png" width="33%">

💡 To see what your post will look like once published, you can click on `Preview` at the top right corner of the Ghost editor. By clicking on the Twitter icon you'll also have a preview of how it will look like when shared on social media or when found on Google. 

12. Create a PR to change the status of the blog post to `ready for publication` in the [post forecast table](https://github.com/meilisearch/devrel/blob/main/communication/post_forecast.md) and add the [desired tags](https://github.com/meilisearch/devrel/issues/466) in the PR comment

## Post-publication corrections
If you realize you need to make corrections after the post has been published, please follow the steps described below:
1. Log in to Ghost with the user editor (bonjour@meilisearch). You can find the credentials on 1Password.
⚠️ If you don't have access to 1Password, ask a member of the Developer Relations team to make the modifications for you. 
2. In the left-hand menu, click on Published (under Posts)
3. Find the post you need to correct (if it was published recently, it should be on the top of the list)
4. Make the necessary modifications
5. Click on the `Update` button on the top right corner of the page
6. Go back by clicking the `< Posts` button located on the top left corner of the page
7. Sign out
