# Media CDN

This repository serves as a Content Delivery Network (CDN) for media files. You can access media files directly using raw GitHub URLs.

## Usage

To access media files stored in this repository, use the following URL format:

```
https://cdn.jsdelivr.net/gh/kore4lyf/public@master/path/to/your/media-file.jpg
```

## URL Structure

The general format for accessing files is:

```
https://cdn.jsdelivr.net/gh/kore4lyf/public@{branch}/{path-to-file}
```

Where:
- `{branch}` is typically `main` (the default branch)
- `{path-to-file}` is the relative path to your media file within the repository

## Examples

### Images
- JPEG: `https://cdn.jsdelivr.net/gh/kore4lyf/public@master/images/photo.jpg`
- PNG: `https://cdn.jsdelivr.net/gh/kore4lyf/public@master/assets/banner.png`
- GIF: `https://cdn.jsdelivr.net/gh/kore4lyf/public@master/media/animation.gif`

### Other Media Files
- Video: `https://cdn.jsdelivr.net/gh/kore4lyf/public@master/videos/demo.mp4`
- Audio: `https://cdn.jsdelivr.net/gh/kore4lyf/public@master/audio/sound.mp3`
- Documents: `https://cdn.jsdelivr.net/gh/kore4lyf/public@master/docs/file.pdf`

## Notes

- Replace `main` with the appropriate branch name if using a different branch
- The file path is case-sensitive
- Files are served with GitHub's global CDN for faster delivery
- There are no restrictions on the types of media files you can store
- As new media files are added to the repository, update the file paths accordingly

## Repository

GitHub: https://github.com/kore4lyf/public
