# tamayo.pictures

Hand-coded static site for tamayo.pictures

## Deploy the site

The site is deployed manually to Fly.io.

```
fly deploy
```

## Generate a new `<article>`

1. Upload `example.png` to Cloudinary `tamayopictures` cloud
2. Run the `pic` util (included with this repo)

Example:

```bash
./pic example.png 'Optional caption'
# or for tall images, e.g. posters:
./pic --tall example.png 'Concert poster'
```
