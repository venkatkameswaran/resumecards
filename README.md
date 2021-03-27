Email me at venkat.kameswaran@gmail.com if you'd like to reach me.

# :briefcase: ResumeCards :briefcase:

ResumeCards is a Markdown based resume generator. It looks great on mobile/desktop and can be saved as PDF.

## :briefcase: Live Demo :briefcase:

### [View Demo and Documentation](http://venkatkameswarn.github.io/resumecards)

![](http://cl.ly/image/3O342N0b0y1h/sample_default.png)

You can save it as PDF too:

![](http://cl.ly/image/091w0b0M2S3G/resume_print_preview.png)

## :briefcase: Installation :briefcase:

**Note:** ResumeCards uses Jekyll. Please read [Jekyll's documentation](http://jekyllrb.com/) if you get stuck.

[Fork this repo](http://github.com/venkatkameswaran/resumecard/fork), clone it, and then run:

```
bundle install
```

...which installs `github-pages` gem. After that, run the server:

```
jekyll serve --watch
```
### Warning

* Once the server is started, you must go to [http://localhost:4000/resumecards/](http://localhost:4000/resumecards/), since `baseurl` is set as `"/resumecards"` initially. To use  http://localhost:4000/, change `baseurl` in `_config.yml` to `""` .

## :briefcase: Usage :briefcase:

### Editing Your Resume

Edit `_posts/card-[1-9].md` like this:

```markdown
---
type: "Work Experience"
heading: "Bizreach"
subheading: "Junior Product Designer"
duration: "October 2013 – September 2014 (1 year)"
location: "Tokyo, Japan"
---

Write in markdown here...
```

If you don't need some of the metadata, just remove them:

```markdown
---
type: "Work Experience"
heading: "Bizreach"
---
```

### Other Files to Modify

You **should** change these files before deploying:

* `_config.yml`: You must change `baseurl`and `url`.
  * Make sure to restart the server after you update `_config.yml`.
* `_data/resume.yml`: You must change `photo`, `name` and `url`. Also, you must set `demo` to `false` to hide everything but your resume.
* `CNAME`: Change this to host ResumeCards on a custom domain.
* `README.md`: Write your own README!
* `_includes/script.html`: Extra stuff before the `</body>` tag. Change or remove the default Google Analytics code.
* `_includes/nav.html`: Modify or remove your contact links.





