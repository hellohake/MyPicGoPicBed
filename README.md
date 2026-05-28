# MyPicGoPicBed

Free image bed for `hellohake.github.io`.

## How to Use

Upload blog images into this public repository, preferably using a stable folder layout:

```text
blog/YYYY/post-slug/image-name.png
```

Use raw GitHub URLs in Markdown:

```md
![alt](https://raw.githubusercontent.com/hellohake/MyPicGoPicBed/main/blog/YYYY/post-slug/image-name.png)
```

Optional CDN URL when jsDelivr is available:

```md
![alt](https://cdn.jsdelivr.net/gh/hellohake/MyPicGoPicBed@main/blog/YYYY/post-slug/image-name.png)
```

Keep filenames ASCII and URL-safe, for example `cover.png` or `diagram-01.jpg`.
