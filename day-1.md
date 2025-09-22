# Day One Learning

## Morning Planning

- [x] This task is complete
- [ ] This task is not complete
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
- [x] #739
- [ ] Review [issue #740](https://github.com/octo-org/octo-repo/issues/740)
- [ ] Add delight to the experience when all tasks are complete :tada:

## Review

```ruby
require 'redcarpet'
markdown = Redcarpet::Markdown.new(Redcarpet::Render::HTML.new)
puts markdown.render("Hello World!")
```

## Example: Terminal Command

```bash
git clone https://github.com/skills/communicate-using-markdown
```

git clone <https://github.com/skills/communicate-using-markdown>

Example JavaScript code

```js
var myVar = "Hello, world!";
```

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
