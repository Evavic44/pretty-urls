<h1 align="center">Pretty URLs</h1>

<p align="center">How to make your static site URLS look like disney princesses using Netlify 👸🏽</p>

Have you ever visited a website and its links looked like this: `www.mywebsite.com/about` or `www.mywebsite.com/blog` and you're wondering how they did, well in this article, I'll be showing you how you can do that in your static html, css, and/or JS site using [Netlify](https://netlify.com)

When I talk about pretty URLs, I'm talking about having a trailing link at the end of your **https:** protocol. Here is an example of what a pretty link looks like and here's another example of what a not-so-pretty link also looks like:

- https://notsoprettylink.netlify.app/about.html
- https://prettylink.netlify.app/about/about

What are the differences between these links and which one is recommended? Basically, pretty links have multiple benefits like

- Better SEO
- Faster redirects and rewrites
- And of course, a cleaner URL

I can't really go into too many details about these benefits but I want you to know I've tested and tried both and every time, pretty URLs were the victor.

**NOTE**
There are other ways and tools for making URLs pretty but we'll be looking at a very simple approach for that. Also, this is a [how-to series](https://eke.hashnode.dev/series/how-to) so I won't be explaining why certain things happen the way they do. If you need more explanation about a certain issue, it means I need to write another article. 🥲 I know, I've been talking too much, I apologize. Here are the steps: 

### Step 1. Create a Netlify Account
[Netlify](https://netlify.com) is the amazing service we'll be using for making our URLs pretty. If you don't know Netlify, it is a free frontend hosting service for web pages. Netlify is an amazing platform used by a huge number of web developers.

To create an account, navigate to their website, create an account and sign in. 
For the sake of this tutorial, I've created 2 projects which were the ones I showed you earlier.

You can test what we'll be building using these links above. Navigate to the contact and about page to see the URLs.

*Simple illustration showing both links*

![notsoprettylink.gif](https://cdn.hashnode.com/res/hashnode/image/upload/v1649226282989/kgxcuYWeq.gif)

### Step 2. Import your project
If you have already uploaded your project to Netlify, then you can skip this step. There are two ways of importing your project to Netlify, dragging and dropping or using a version control platform like GitHub, Gitlab, or BitBucket.

For simplicity, we'll be using the drag and drop feature and for the code, I'm using Netlify's [parody site](https://github.com/netlify/netlify-drop-demo-site/archive/master.zip). I updated it a little and added an about and contact page so we can see the changes when we switch between them. Visit https://app.netlify.com/drop, drag the project folder, and drop it into the dashboard. 

![drag-and-drop-dashboard.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1649227101007/SvV8GvClz.png)

This will propagate for a few minutes and when it's done, a link will be auto-generated by Netlify that we can visit to see our project live. 

![pretty-urls-weird-name.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1649227179871/d7z-PN9al.png)

 ### Step 3. Enable Pretty URLs
Now we have successfully uploaded our project to Netlify, we can now enable the pretty URLs. To do this, click the **deploy** link on the top > **deploy settings** and then scroll to **assets optimizations** section. 

![deploy-settings.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1649227258791/g_PkR8ZeM.png)

Click the **edit** settings button, you'll see some options greyed out. Uncheck the asset optimization box and then select only **pretty URLs** then hit save. 

![pretty-urls-checkbox.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1649227269794/yq1bQGcso.png)

That's all, yes that's all. Now refresh the page to see your pretty Disney princess links

### Pretty Link

![prettylink.gif](https://cdn.hashnode.com/res/hashnode/image/upload/v1649226299418/5mizgxX9Z.gif)

Here's the other parody site with pretty URL enabled. We can see our links are looking a lot better now. 🙂


### [File-based configurations](https://docs.netlify.com/configure-builds/file-based-configuration/#sample-netlify-toml-file)
You can even do more awesome stuff with URLs with Netlify like [creating redirects and rewrites in Netlify site](https://docs.netlify.com/routing/redirects/#syntax-for-the-redirects-file). In addition to using the Netlify UI to configure build settings, deploy settings, environment variables, and asset optimization settings, you can also configure these settings in a [`netlify.toml`](https://docs.netlify.com/configure-builds/file-based-configuration/#sample-netlify-toml-file) file.


-----------------------------------------------------------------------------------------------------
Want to learn more about Netllify, here are some cool resources and tutorials you can check out. 

[Introduction to Netlify](https://link.com) <br>
[How to host a frontend project with Netlify](https://link.com) <br>
[Blah Blah Blah](https://link)

If you found this article very helpful, do share it with some of your friends and I'll see you all in the next episode.

> Happy coding and don't let the code bugs bite. 🪲


## ⚡ Attribution
This is a demo site by [Netlify](https://netlify.com). Modified and uploaded for teaching how to make links pretty using Netlify Pretty URL feature. 

### Thanos JS (demo site)
Silly demo site to be used for [Netlify Drop](https://app.netlify.com/drop).

Preview demo site [right here](https://www.thanosjs.org).

Thanks to [Rasmus Andersson](https://twitter.com/rsms) for creating [Inter UI font](https://rsms.me/inter/).

