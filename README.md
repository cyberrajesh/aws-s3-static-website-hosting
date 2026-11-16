[README_S3.md](https://github.com/user-attachments/files/34900339/README_S3.md)
# Static Website Hosting on Amazon S3

A static website (HTML, CSS and JavaScript) hosted on **Amazon S3** using the static website hosting feature.

## Architecture

```
User (browser) -> S3 static website endpoint -> S3 bucket (website files)
```

## Tech Stack

| Area | Tools |
| --- | --- |
| Cloud | Amazon S3 (static website hosting) |
| Access control | Bucket policy, public access settings |
| Website | HTML, CSS, JavaScript |

## Repository Structure

> Edit this list to match your real files.

| File / Folder | Purpose |
| --- | --- |
| `index.html` | Home page (index document) |
| `error.html` | Error page, if you used one |
| `css/` | Stylesheets |
| `js/` | Scripts |
| `images/` | Images |
| `bucket-policy.json` | Policy that allows public read access |
| `screenshots/` | Proof of the working setup |

## Setup Steps

> Check each step against what you actually did.

1. Create an S3 bucket.
2. Turn off "Block all public access" for the bucket.
3. Upload the website files.
4. Enable static website hosting and set `index.html` as the index document.
5. Add a bucket policy that allows public read access to the objects.
6. Open the bucket website endpoint in a browser to test.

## Screenshots

- Add a screenshot of the S3 bucket with the uploaded files.
- Add a screenshot of the static website hosting setting.
- Add a screenshot of the live website in the browser.

## What I Learned

- Creating and configuring an S3 bucket
- Enabling static website hosting
- Writing a bucket policy to control public access

## Author

**Rajesh S** | rajeshdece2001@gmail.com
