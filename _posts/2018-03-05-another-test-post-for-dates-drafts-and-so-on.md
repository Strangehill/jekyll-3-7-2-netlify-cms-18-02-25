---
layout: post
title: 'another test post for dates, drafts, and so on'
---
I tested a post previously that triggered an error-free deploy but did not result in a blog post. This blog post I'm creating under very likely very similar conditions. That previous post since been rendered to the site. I expect this test post to not render in the immediate minutes after deploying. I suspect it's got something to do with the filename of the post indicating a date that is a future date relative to the date used by the 'build and deploy' netlify process.

EDIT:
=====

My suspicions were confirmed. After this post did not render I changed its filename on github to assign it a one day earlier date which triggered a deploy which did in fact render this blog post.
I'm now looking at this site's deploy setting's, in particular with an eye to 'environment variables' (which is a topic I've yet to really grok)
