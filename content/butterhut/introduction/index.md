---
title: "Introduction"
weight: 0
lede: "Why don't we just purchase a shed and put it on flat land"
description: "The backstory to the Butterhut — why timber frame and why this particular hill"
draft: false
---

{{< comment >}}
Weight 0 keeps this out of the numbered build phases and lists it under
"Start here" on /butterhut/ instead. No status tag and no date, on purpose —
the introduction is the one page that should not read as dated.

Below is a skeleton, not text to keep. Rewrite all of it.
{{< /comment >}}

## The Backstory

{{< comment >}}
The site itself. What was there before, how long you have looked at it,
what made it the place. A photo of the bare hill belongs here — it becomes
the "before" image the whole project is measured against, and it is the one
photograph you cannot go back and take later.
{{< /comment >}}

## The Location

{{< comment >}}
The honest answer. Not "it is traditional" but whatever actually drew you:
the joinery, wanting to work at a scale a person can hold in their head,
having spent a career on things that are assembled rather than built.

There is a real thread here worth naming — a career designing hardware that
has to survive an MRI bore, and a building held together by wood cut to fit
wood. Both are about tolerances and about what happens at the joints.
{{< /comment >}}

{{< comment >}}
====================== PHOTO REFERENCE ======================

Photos go in this folder, beside this file:

    content/butterhut/introduction/
      index.md
      bare-hill.jpg      <- just drop it here

Reference by bare filename. No path, no ../, no /static/.

    ![Alt text, describing what the photo shows.](bare-hill.jpg "Optional caption. Takes *markdown*.")

Alt text is required and is what a screen reader and a search engine see.
The caption in quotes is optional and renders under the photo.

Hugo does the rest: webp, four widths, srcset, correct dimensions so the
page doesn't jump, lazy loading, GPS stripped. Put the FULL RESOLUTION file
in — it needs the big one to make the small ones, and it caches the work.

Name files lowercase-with-hyphens and descriptively. You will have hundreds,
and the filename is the only handle you get. pier-hole-northeast.jpg, not
IMG_4471.JPG.

Two side by side — raw HTML, because the markdown shorthand can't express it.
Note this bypasses the resizing pipeline and serves the original file, so it
is fine for modest images and bad for two 12MP ones:

    <div class="pair">
      <figure><img src="before.jpg" alt="Before clearing."><figcaption>March.</figcaption></figure>
      <figure><img src="after.jpg" alt="After clearing."><figcaption>May.</figcaption></figure>
    </div>

==============================================================
{{< /comment >}}

## The Idea
