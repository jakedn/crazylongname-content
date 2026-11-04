# Content

Notes, posts and images for the site. Built and deployed by the
[`crazylongname-site`](https://github.com/jakedn/crazylongname-site) repo, which clones this
repo into `src/content` at build time.

```
notes/         *.md  -> /notes/...
posts/         *.md  -> /posts/...
attachments/   images, referenced from content as /images/public/<file>
```

Content is written in Obsidian and synced here from the Mac; don't hand-edit
files here unless you also update the vault. Layouts are assigned by the site
from the folder, so files need only front matter (`title`, `date`, `permalink`,
optional `description`, `image`, `tags`).
