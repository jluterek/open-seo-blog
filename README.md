# Open SEO Blog

This project contains the blog used by [open-seo.org](https://www.open-seo.org/blog/)

The blog is built using [hugo](https://gohugo.io/).  We accept submissions for SEO related topics, especially those featuring open source software.

## Running the blog local

 * Download or fork this github repo.
 * [Install Hugo.](https://github.com/gohugoio/hugo/releases)
 * Run "hugo server" to launch a local instance.

## Contributing

So you want fame, fortune, and backlinks by posting yoru content here?  No problem, just follow these steps:

### Step 1: Fork the github repository

You need to **fork the git repo** on which this site is hosted: [https://github.com/jluterek/open-seo-blog](https://github.com/jluterek/open-seo-blog).
Go to this repository and in the top righthand corner, click the Fork button.
This creates your own copy of the repo in your GitHub account.

Now, you need to clone the repo onto your local machine (I'm assuming you have git installed) git clone https://github.com/YOUR-USERNAME/open-seo-blog

Next, create a new branch on your local machine (`git checkout` is for switching branches and the `-b` flag says to create a new branch).
You need to **make your changes on this new branch**.

git checkout -b NAME-OF-NEW-BRANCH

Now you should have all the files necessary.

### Step 2: Write your blog post using Markdown

Write your blog post as a Markdown file, and save your `.md` file in the `/content/post` folder.  You can include custom HTML if necessary, but make sure you browser test any code.

Follow this convention when naming your file `YYYY-MM-DD-blog-post-name.md` :point_right: `2016-01-27-post-title-here.md`

> New to markdown? [Read this](https://guides.github.com/features/mastering-markdown/)

You *do not* need to compile this file into html anywhere.

Any images used should be added to the 'static/img' folder.  Please organize them by date (YYYY-MM-DD/filename.jpg).

Be sure to include all meta information at the top of your markdown file, including author information:

---yml

author: "John Doe"
date: 2017-09-28
linktitle: Creating a New Post
title: Creating a New Post
weight: 10

---


Once you're done, add and commit your blog post:

git add FILENAME
git commit -m "A brief message about what files you're adding"

### Step 3: Submit a pull request

Now that you're all done adding things, you need to merge it into the website.
You do this in two steps: you'll push it to your GitHub repo and then submit a **pull request**, asking us to pull your changes into the website.
First, push your changes to your repo:

git push origin NAME-OF-NEW-BRANCH

Now, navigate back to [the original repo](https://github.com/jluterek/open-seo-blog).
At the top of the repo, the new branch will show up with a green Pull Request button - click it and submit the request.

Now, we will either merge your changes into the website, or ask you to make modifications, or change the post to match our requirements.  Open SEO reserves the right to edit any blog posts before publishing.

## That's too difficult

While learning to use source control is a valuable skill, if you are having trouble I will accept submission by email.  Visit [https://www.open-seo.org/blog/contact](https://www.open-seo.org/blog/contact) to get started.