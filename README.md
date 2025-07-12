# AMC Squad website

Here's some quick documentation on how to edit the site. If you have any trouble, holler at ya boi
`ektoutie` on the AMC Discord.

## Updating the site

If any changes have been made to the site, it must be rebuilt and re-deployed for changes to be
visible. This should happen automatically on any change to the `main` branch in this git repository
and progress should be visible in the [Actions](https://github.com/amcsquad/amcsquad.github.io/actions)
tab on the repo.

Changes made on branches will never be pushed to the live site; only changes to `main` get published.
However, opening a PR or adding more changes to an existing one will run a build and some linting
tools to make sure the site code is working and clean.

If for some reason the automatic deployment does not work, any Github user with write access to this
repository (currently `ektoutie` and `doom64hunter`) can manually trigger the process by using the
`Run workflow` button on the
[Jekyll CI workflow page](https://github.com/amcsquad/amcsquad.github.io/actions/workflows/jekyll.yml).

## I want to post a blog thing!

Create a file in [`_posts`](https://github.com/amcsquad/amcsquad.github.io/tree/main/_posts);
see the existing files for examples. Formatting is done using [Markdown](https://www.markdownguide.org/);
if you want a web-based editor with preview for this check out [StackEdit](https://stackedit.io/app#).

### Post date

Prefix the post filename with the date in `YYYY-MM-DD` format to set the displayed post date,
e.g. `2025-07-12-done-a-thing.md`.

#### NOTE:
  - Future-dated posts will obviously be publicly visible in this GitHub repository
    as soon as they're added.
  - However, future-dated posts will not appear on the site until the first time the
    site is re-deployed after their publishing date.
  - This will **not** happen automatically. Someone needs to press the button (as above).

If you want to make a semi-secret post for the future, the best procedure is:

  - Fork this github repository
  - Add your post on your personal repo
  - Create a Pull Request for new post when you want it to be published
  - Once someone else with write access here has reviewed and approved the post, it'll go live.

### Post header

Each post must have a header section following this format:

```yaml
---
title: Posting from the future~
layout: post
image: https://img.youtube.com/vi/i1am9twB_Q0/0.jpg
description: Come get your teaser video here!
tags:
- game
- info
---
```

The field names should be pretty self-explanatory.

### Post images

If you add an image, simply also copy this to [`assets/images/blog/`] and set the `image` field in the
post header to its filename. Posts that have no `image` set, or have an image set that doesn't
exist, will display the [default image](https://github.com/amcsquad/amcsquad.github.io/blob/main/assets/images/blog/default.png).

## I want to update my credits info!

Simply edit the file [`_data/credits.yml`](https://github.com/amcsquad/amcsquad.github.io/blob/main/_data/credits.yml).
The format is pretty human-readable so I'm sure you can figure it out. If you want to add/update an image for the
credits, these are stored as a bucket of `.png`s in
[`assets/images/portraits/`](https://github.com/amcsquad/amcsquad.github.io/tree/main/assets/images/portraits/).
