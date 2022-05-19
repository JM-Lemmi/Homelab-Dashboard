# Homelab-Dashboard

A Simple dashboard for your homelab using bootstrap. Inspired by a post at /r/selfhosted. It's free to use and you can modify it, just don't sell it.
It's pretty simple just put it in your web server's public html folder.
It simply runs with Bootstrap-CSS and HTML. There are no scripts running at all. All you need to do is add your own links and titles.

## Filling

There are three different types of Dashboard-Boxes:
* Dark-blue (`div class="panel panel-primary"`)
* Light-blue (`div class="panel panel-info"`)
* Green (`div class="panel panel-success"`)

You can add an icon by adding an image into the link in a `list-group item`.

## Contribution

### Reduce the original css

```
npm i -g purgecss
purgecss --css ./main.css --content ./index.html --output ./main-purge.css
purgecss --css ./theme-min.css --content ./index.html --output ./theme-min-purge.css
```
