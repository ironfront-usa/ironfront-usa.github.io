# Guidelines for Contributing a Blog Post

## How do I even start?

Well, first things first! You have to write the post. Talk about you personal
experiences with patriotism, antifascism, community action, etc. We have no
formal page limits, though we encourage making posts in multiple parts if you
feel like you have a lot to say.

Our site hosts blog posts in markdown (specifically
[GFM](https://github.github.com/gfm), which is a plain text format for writing
structured documents. If you feel comfortable writing documents using markdown,
please feel free to! Otherwise we recommend using your favorite rich text
editor, such as Microsoft Word or Google Docs, and then converting a `.docx`
file format to markdown using a tool like this [converter](https://word2md.com/)
to translate your doc into markdown that can be hosted on the site.

## All of this technical stuff is so beyond me!

That is totally fine! You can write your blog post regularly, and then contact
a site admin either through our email or by 
[creating an issue](https://github.com/ironfront-usa/ironfront-usa.github.io/issues).

## What happens next?

Then your issue will be addressed by the site's editors, who will interact with
you through your issue ticket. Here, they will suggest edits to your post and
when it is finished, close the issue and send it off to the site reviewers. 
These reviewers will finalize the markdown boilerplate so that the post shows
up correctly on our blog, and finally merge it to the website.

## I understand how git works.

Okay, awesome! In that case, we recommend cloning our master branch to your own
machine and adding your blog post to the `./_posts/` directory. Your blog post
should be a file named according to `YYYY-MM-DD-title.md` and should look like
this:

```markdown
---
layout: post
title: "Title"
date: YYYY-MM-DD
---

<!-- your post markdown here -->
```

Save and commit. Then, push your new version fo this repository to your personal
github and [submit a pull request](https://github.com/ironfront-usa/ironfront-usa.github.io/pulls). 
This will automatically create a new card in our project reviewer's TODO list,
where editors will make suggestions.

