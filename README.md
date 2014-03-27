alfred-octopress
================

This Alfred extension automatically creates a post and opens the markdown file for it in your editor of choice (it uses Mou by default).

Usage:
Set the `OCTOPATH` variable to your octopress installation directory and `EDITORAPP` to your favourite editor.

```
  blog Awesome post
  #Create a new blog post, named "Awesome post"
  blog generate
  #Launch static page generation via Jekyll.
```

add by ungacy
start
add codes below to auto deploy to github.

```
git add . 
git commit -am $(date +%Y-%m-%d)
git push origin source
rake deploy >> /dev/null
```
end
Alfred workflow bundle can be downloaded [here](https://github.com/ungacy/alfred-octopress/blob/master/bundle/Octopress%20publish.alfredworkflow).