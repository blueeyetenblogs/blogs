---
layout: post
title: "Almost Free Website"
---

Here's a tech hack to create your own almost free website. Mostly what influencers tell you as their own idea.

1. Type in "How to create github pages" in Google. Google's AI engine will give you the steps. Follow that.
    1.1 Create a new repository: Name the repository exactly as <username>.github.io (for a user page) or <organization>.github.io (for an organization page). Ensure it is public.
    1.2 Add your website content: Create an index.html file (or index.md, README.md) in the root of this repository and add your website's content. You can also include CSS, JavaScript, and other assets.
    1.3 Enable GitHub Pages: GitHub Pages is automatically enabled for repositories named <username>.github.io or <organization>.github.io. Your site will be published at https://<username>.github.io or https://<organization>.github.io.

2. Type in "How to connect custom godaddy domain with Github pages". Follow the instructions. Mostly change your DNS record.

    1. Create A records pointing to GitHub's IP addresses. You will typically need to add four A records for @ (or your root domain) pointing to:
        >      
        185.199.108.153
        185.199.109.153
        185.199.110.153
        185.199.111.153

    2. For a www subdomain (e.g., www.example.com): Create a CNAME record for www pointing to your GitHub Pages URL (e.g., your-username.github.io).

    3. Wait for it to configure. Go the the domain to see it is working

4. Type in ChatGPT "Create a blog site that can be put in github pages. The site is to write about my experiences, travel, techs and my job related blogs. Make it elegant and simple.". Follow the instructions. I used the Jekyll way. You can look at the files under my github repo [blueeyeten](https://github.com/blueeyetenblogs/blogs).

5. Search for Google Analytics. Create a free account. Copy the script inside your head tag. Now you have analytics. Know how many have seen your site.

6. You are in my completed site

Will take care of security and mail list later.