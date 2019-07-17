---
title: "Comments for static sites"
categories: [site-development]
header:
  teaser: /posts-images/shitty-comments.jpg
---

I would like to thank [Nicolas Hoizey](https://nicolas-hoizey.com/2017/07/so-long-disqus-hello-webmentions.html) for introducing me to [webmentions](https://webmention.io/)
and [Bridgy](https://brid.gy/).

Glad to know that I'm not alone in thinking we netizens shouldn't always rely on centralized internet services such as Disqus, Facebook, and even Twitter, in spite of 
the ease of use, we should be independent of them.

Also [Chad Lee's post](https://www.chadly.net/embracing-the-indieweb/) provided the perfect use of the H-Card and H-Entry for Microformats.

This all started when I was looking for a commenting system for my static blog. Most don't like commenting through Facebook and Disqus because they are heavily moderated by
parent sites - no negative comments allowed even if it's the truth.

I'm also excited to see what my comment will look like when it comes out in Aaron Parecki's test [post](https://aaronparecki.com/2018/06/30/11/your-first-webmention).

### What You Need

1. Add an [H-Card to your website](https://indiewebify.me/) so you can use your social media credentials to log in to Indieweb websites.
2. Sign up to <https://webmention.io/> and <https://brid.gy/>. Bridgy will poll all your Twitter and Instagram posts mentioning your website/blog and then it will ping 
Webmention in your behalf the replies you get from those sites and then Webmention.io will host all your webmentions in which you can then display in your site.
3. Install the <https://github.com/PlaidWeb/webmention.js> so that you can render the comments in your static site via javascript.
4. For commenting on Webmention-enabled sites, I like using <https://telegraph.p3k.io/>.

Good Luck!

 