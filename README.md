# Blog
Check it out at [kungfux.github.io](https://kungfux.github.io)

# Rules
- Image format is `.webp`
- Cover image size `1200 x 630` with aspect ratio of `1.91 : 1`

# Development
## Commands
- Restore
```bash
$ bundle
```

- Build
```bash
$ bundle exec jekyll
```

- Include drafts into build
```bash
$ bundle exec jekyll --drafts
```

- Build and watch
```bash
$ bundle exec jekyll s
```

## Upgrade
1. Update version number
```diff
- gem "jekyll-theme-chirpy", "~> 3.2"
+ gem "jekyll-theme-chirpy", "~> 4.0"
```

2. Run `bundle update`

## Customizations

- Embed video file
```
_includes\embed\video.html
_includes\embed\customvideo.html
assets\css\jekyll-theme-chirpy.scss
```

- Add page views counter
```
_includes\views.html
_layouts\post.html
```

- Wrap text in code blocks
- Adjust styles for schemas and code blocks
- Align lists by center
```
assets/css/jekyll-theme-chirpy.scss
```