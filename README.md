## mvmfc

Martha's Vineyard Model Flying Club Website

## Installation

```
git clone https://github.com/bcarreno/mvmfc.git
jekyll serve --watch
```

## Deployment

```
jekyll build
rsync -avz --delete _site/ my_website.com:/home/my_user/mvmfc
```
