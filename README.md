# Commands

* rake publish (calls generate, then executes publish task), updates directory _site with the 'built' site  
```$ rake publish```

* rake post (creates a file in source/_posts for user to edit and add to it)  
``$ rake post title="my new post" tags="tag1,tag2" category="vacation"``

* rake page (create a new page )  
`` $ rake page name="the_new_page_name"``



### Start in 4 steps

1. Download or clone repo `git clone git@github.com:nandomoreirame/end2end.git`
2. Enter the folder: `cd end2end/`
3. Install Ruby gems: `bundle install`
4. Start Jekyll server: `bundle exec jekyll serve`

Access, [localhost:4000/end2end](http://localhost:4000/end2end)

### Deploy in Github pages in 2 steps

1. Change the variables `GITHUB_REPONAME` and `GITHUB_REPO_BRANCH` in `Rakefile`
2. Run `rake` or `rake publish` for build and publish on Github

---

### Using Rake tasks

* Create a new page: `rake page name="contact.md"`
* Create a new post: `rake post title="TITLE OF THE POST"`

---

### Demo and Download

[Demo](https://nandomoreirame.github.io/end2end/)
---


