# FROM DAD'S IPHONE PHOTOS: publishing guide

This folder is for real, family-approved posts. No launch stories, dates or personal experiences have been invented.

## Add a post
1. Create a descriptive HTML filename in this folder, using lowercase words and hyphens. Use a real title, not an empty stub.
2. Use a complete HTML document with lang=en, charset=utf-8, a viewport meta tag, and the real post title in title and h1. Add an article element for the complete approved story. Date it only when the author supplies the actual publication date.
3. For the lane's full visual style, copy ../index.html as your starting HTML, keep its style block and body class (photo), and replace main with the actual article. Because posts are one directory deeper, change header and footer home/freebies/shop links from ../../index.html to ../../../index.html and the hub link from ../../family/index.html to ../../index.html. Add a Back to this lane link with href=../index.html. Replace the generic meta description with an accurate description of the post.
4. Use only approved images and alt text; store images in this posts folder or a child images folder and use relative links. Do not publish identifying locations, private family matters, clinical or medical information, or another person's words without their approval. No invented quotes, stories, or dates.
5. Update ../index.html: in the section with class=stories, replace the no-posts-yet sentence, remove hidden from ul#post-list, and add one li containing an article, an h3, and a real-title link to posts/YOUR-ACTUAL-FILENAME.html. Add a short accurate excerpt if useful. Put newest posts first. Keep the shared line, Stories land here as they're written.
6. Commit the new post and lane index changes to main. GitHub Pages deploys automatically. Open the live post and check the lane listing, navigation, images, and mobile layout.

## URLs and ownership
Lane: https://kevinjc0peland.github.io/champs-adventures/family/dads-iphone-photos/
Post directory: family/dads-iphone-photos/posts/
This README is an authoring guide, not a blog entry, and is not listed as a published post.

Only edit this Champs Adventures repository. The separate coaching site must not be changed.
