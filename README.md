# Amirhossein Asadi — personal website

Live at https://amirhosseinasadi1380.github.io

- `index.html` — the whole site (about, news, selected projects, cv) on one scrolling page
- `photo.jpg` — profile photo

To add or edit a project, edit the `PROJECTS` list near the bottom of `index.html`.
To use a real image for a project, put it in `images/` and set `img: 'images/name.png'` on that project.
The tags under each project come from that project's `papers` entries: `arxiv`, or else `pdf`/`doi` for a published paper (labelled with its `venue`), plus `code`. A paper with an arXiv link shows only the arXiv tag. A tag listed in `soon` shows as a dashed "coming soon" tag until its real link is added.
To add news, copy a `<tr>` row in the news table.
