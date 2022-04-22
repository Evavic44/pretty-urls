<h1 align="center">Pretty URLs</h1>

<p align="center">How to make your static site URLS look like disney princesses using Netlify 👸🏽</p>

When you build a static site that has an about or contact page, by default the URL ends with a `.html` extension whereas, on modern sites we see today, the links do not have this extension when you visit these pages. These are what we call pretty URLs, AKA user-friendly URLs, intended to improve the usability and accessibility of a website or web service by being immediately and intuitively meaningful to non-expert users. Example: [www.netlify.com/about](https://netlify.com/about) and [www.hashnode.com/about](https://hashnode.com/about). Wondering how they did it? in this article, I'll explain how you can do that in your static html, css, and/or JS site using [Netlify](https://netlify.com)

### Step 1. Create a Netlify Account
[Netlify](https://netlify.com) is the service we'll be using to make our URLs pretty. If you don't know Netlify, it is a free frontend hosting service for web pages.

To create an account, navigate to their website, create an account and sign in. 
For the sake of this tutorial, I've created 2 projects so you can test what we'll be building using these links. Navigate to the contact and about page to see the URLs.

![not-so-pretty.gif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650574690545/Or7w4ydEL.gif)

### Step 2. Import your project
If you have already uploaded your project to Netlify, then you can skip this step. There are two ways of importing your project to Netlify, dragging and dropping or using a version control platform like GitHub, Gitlab, or BitBucket.

For simplicity, we'll be using the drag and drop feature and for the code, I'm using Netlify's [parody site](https://github.com/netlify/netlify-drop-demo-site/archive/master.zip). I updated it a little and added an about and contact page so we can see the changes when we switch between them. Visit https://app.netlify.com/drop, drag the Netlify pardoy site, and drop it into the dashboard. 

![netlify-drop.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1650574884608/pNaR2yjm4.png)

This will propagate for a few minutes and when it's done, a link will be auto-generated by Netlify that we can visit to see our project live. 

![not-so-pretty-url.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1650575338317/K7mVXKREy.png)

 ### Step 3. Enable Pretty URLs
To do this, click the **deploy** link on the top > **deploy settings** and then **post processing**.

![deploy-settings.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1650575799262/GbRQcMQX8.png)

Click the **edit** settings button, you'll see some options greyed out. Uncheck the asset optimization box and then select only **pretty URLs** then hit save. 

![asset-optimizations.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1650576376292/3xOp4wcKF.png)

*Voila!* Now refresh the page to see your pretty URLs. 🙂

![pretty-url.gif](https://cdn.hashnode.com/res/hashnode/image/upload/v1650577546464/W0AyrdE4r.gif)

If you found this article helpful, leave a comment below or follow me for similar content and I'll see you in the next series. Bye. 

<details>
<summary>Socials</summary>
<a href="https://github.com/evavic44">GitHub</a></br>
<a href="https://twitter.com/evavic44">Twitter</a></br>
<a href="https://www.linkedin.com/in/evavic44/">Linkedin</a>
</details>


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

