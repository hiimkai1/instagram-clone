# Instagram-clone
This is an instagram like clone built with python and flask.

## Current Features
- Upload images with captions and option to delete posts.
- Comment on posts and option to delete them
- Like/unlike posts
- Follow/unfollow users
- Feed consists of posts from users you follow 
- Explore page shows posts from all users
- Notifications on activities on your posts.
- Change profile pic and username
- Suggestions to follow users

## Features to add
- Tag feature
- Search option for users and tags
- Display followers/following (on profile)

## Running Locally

Follow these instructions to get this project up and running on your machine.  

### Prerequisites
1. Postgresql database
2. AWS S3 bucket

### Installing
```
git clone https://github.com/hiimkai1/instagram_clone.git
cd ig_clone
pip install -r requirements.txt
```

Set environments for the following:

```
DATABASEURL=postgresql://<host><:port>/<database_name>
S3_BUCKET=<bucket_name>
S3_ACCESS_KEY=<access_key>
S3_SECRET_KEY=<secret_key>
```

Set ```debug=1``` on main.py
