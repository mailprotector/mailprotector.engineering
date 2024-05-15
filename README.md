# Mailprotector Engineering Blog

This is the official blog for the Mailprotector Engineering team. We will be posting about our experiences, challenges, and solutions as we work to build the best email platform in the world.

## Post ideas

When you have an idea for a post, you can create a new issue in the repository. This will allow you to get feedback on your idea and collaborate with other team members. Assign the team member(s) you think would be interested in contributing/writing on the post to the issue.

## How to create a post

To create a new post, simply create a new markdown file in the `_posts` directory. The file should be named with the following format: `YYYY-MM-DD-title.md`. The file should start with the following front matter:

```yaml
---
layout: post
title: Title of the post
subtitle: Subtitle of the post
cover-img: /assets/img/path.jpg (optional)
thumbnail-img: /assets/img/placeholder-wrap-theo.png (optional)
share-img: /assets/img/placeholder-wrap-theo.png (optional)
tags: [tag1, tag2]
author:
  name: Your Name
  title: Your title
---
```

After the front matter, you can write your post in markdown. You can use the [markdown tutorial](https://markdowntutorial.com/) to learn how to write in markdown.

## Drafts

Drafts are posts without a date in the filename. They’re posts you’re still working on and don’t want to publish yet. There is a `_drafts` folder for drafts. To preview your drafts, run the blog locally via docker.

## How to preview the blog

To preview, you can run the following command:

```bash
docker compose up -d
```

This will start a local server that you can access at `http://localhost:4000`. You can see your post by navigating to `http://localhost:4000/title`.

## How to publish your post

To publish your post, create a pull request with your post. Once merged, the post will be published to the blog automatically. It takes about 1-2 minutes for the site to update with the new content. You can check the status of the build in the Actions tab.
