# Secure Systems Lab website

This is the website for the Secure Systems Lab. You can see a live demo of this site at [dgopstein.github.io/ssl-site/](dgopstein.github.io/ssl-site/)

## Building locally

Before committing changes, please make sure you commit looks good by checking your change locally.

- Open a terminal and `cd` to the directory where you've checked out this project
- *First time only* install necessary ruby packages with `bundler install`
- Run the local jekyll server: `jekyll build --trace  --baseurl '/' && jekyll serve --incremental --port 7000 --baseurl '/'`
- View your draft at [localhost:7000](localhost:7000)
- Most files will be automatically re-processed as long as the server is running, if you edit a *.yml* file, however, you will need to manually kill the server and re-run the build command.

