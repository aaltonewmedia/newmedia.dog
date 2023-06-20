---
title: "Help"
draft: false
weight: 90
bookCollapseSection: true
---

## Aalto New Media Student Sites

This website is for you to use as a public documentation site and archive for your course projects and other things that you would like to share with the world. Some of the courses will specifically ask you to use this as your documentation site, but feel free to document other courses or projects here as well.

## Getting started

### The 5 minute video

Coming soon...

### Access

All of your content is stored on [version.aalto.fi](https://version.aalto.fi/gitlab/), the Aalto instance of GitLab. In order to get your own section on the website, you need to do the following:

1. Check that you can access and login to [version.aalto.fi](https://version.aalto.fi/gitlab/) using your Aalto account.
2. Ask Matti to add you to the New Media team. Also let him know what name you want to use for your section. We prefer that you use your real name, but it's not a requirement. See the FAQ.
3. Once Matti or one of the assistants has added you to the team, you can start adding content.

Get familiar with Matti's example that shows you what kind of features are available:
- [Example section](example/matti-niinimaki)
- [Repository](https://version.aalto.fi/gitlab/aalto-media-lab/new-media/matti-niinimaki)

### Editing your landing page

The site is built using a static-site generator called Hugo. You create and edit content by adding new markdown-formatted files to your repository. If you are not familiar with git, GitLab and all of the other technical aspects, you can start off by just using the website editor on version.aalto.fi.

1. Replace the placeholder image called `featured.jpg` with a picture of yourself or any other image that represents you in some way.
2. Update the _index.md file on the top level of the folder with any basic information of you that you want to share (any social media links, LinkedIn profile, your own website etc.). **Note that you are not required to share anything that you don't want.**
3. Commit any changes that you would like to have published to the site.
4. Keep in mind that your commited changes will not show up immediately on the site. Matti pulls all the changes periodically. If you wish to see how your changes would look like while you work on it, you need to setup your own local version of the site. (See instructions below).

## Adding new sections and content

### Structure

### Formatting

#### Images

Please follow these guidelines for images:
- The file size for any image should be less than 2MB, ideally much smaller
- The longer side of your image should be maximum 1500px
- Horizontal images work best on this site

#### Videos

If your video file is small (under 50MB), you can upload it directly to your repository. Otherwise, upload videos to some Aalto service like Panopto or to the Aalto Media Lab Vimeo or YouTube channels. If you are in a hurry, you can upload the file to your own video sharing account, but let's try to eventually upload all videos to our accounts so that we do not lose them.

Please follow these guidelines:
- Resolution: 1920 x 1080
- **No vertical videos**
- .mp4 file
- H264 or some other web-friendly coded
- Try to keep the file size under 10MB, the maximum size is 50MB


There are multiple tools available for compressing your videos. These are some recommended options:
- HandBrake

##### Vimeo

Use the Vimeo shortcode:

```go
{{</*vimeo video_id*/>}}
```

##### YouTube

Use the YouTube shortcode:

```go
{{</*youtube video_id*/>}}
```

#### Video files from the repository

We have a Hugo shortcode available for embedding video files directly from the repository. Please follow the instructions carefully as this will break the site if done incorrectly: (instructions coming soon)

### Code

---

## FAQ

Why? What? How?

### Why do we have to do this?

It has become painfully obvious over the years that we have lost so many amazing projects to the depths of the Internet, MyCourses assignments etc. This site is an attempt to collect an archive of projects that we can come back to later or to proudly share with the world. Additionally, this has a pedagogical purpose. You will learn how to use version control systems (git), work with static site generators (hugo), and to generally keep a detailed documentation of your work. We hope that this will get you curious about creating your own websites.

### What if I do not want my name or other information visible publicly?

If you wish to be more anonymous for whatever reason, you can make up a fake name or use just your initials. Let Matti know about this so that we can make you a new project in GitLab without your name or other personal information. I would recommend using your own name as this site can help you find opportunities outside the university.

### What if I don't like how this site looks like?

Make a better version and send it to Matti as a pull request. If enough people like your version better, we can switch to that. This site is built with Hugo with a custom theme so testing different versions is pretty easy as long as your theme supports all the custom features we have added. You can find the entire source here: (link TBC). I also highly recommend that you make your own portfolio site. You can add links to that from your page.

### Why can't I just use my own site?

You can, but you have to use this as well for certain things. Domains expire, you might end up deleting things, forget to pay for hosting etc. The key thing is that things disappear from the Internet very easily and then they are often lost forever or very hard to find again. You can always link to your own site(s) from here for more information.

### Can I browse the other student sites for help in my projects?

Yes, that is the point. We all stand on the shoulders of giants and learning from your peers is one of the most valuable things that you have access to here at Aalto. Just remember to give credit to where you found help or solutions. You will also notice that sometimes you need to come back to your own notes and documentation to remeber how to do something.

### Why do we use Hugo and not something easier like Wordpress?

1. Static websites load a lot faster and use less energy and other resources. The Internet uses a lot of energy and I would rather minimize our impact. I recommend comparing different sites using this tool: [https://www.websitecarbon.com](https://www.websitecarbon.com). See how this one compares to some others.
2. Wordpress maintenance and security is quite painful for sites that need to exist for a long time.
3. All of our content and the different versions of it will be stored using GitLab. So even if this site itself dissapears all of the content should be possible to move somewhere else fairly easily.

### Why don't we just use the Drupal on aalto.fi?

Don't get me started on that...

---