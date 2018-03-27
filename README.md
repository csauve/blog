# t3hz0r.com
Blog content and static site generator for my personal blog, https://t3hz0r.com.

## Building and deploying
```sh
npm install

# build & testing:
npx gulp
npx gulp && http-server ./dist/

# deploy to prod
aws s3 sync --delete ./dist s3://t3hz0r.com/
```

## Todo
* Solve permalinks & moved content
* Post footers
* New content
* Blogroll/links
* Continuous deployment
* RSS