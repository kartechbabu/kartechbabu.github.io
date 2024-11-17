## Using Docker

Working from a different OS, or just want to avoid installing dependencies? You can use the provided `Dockerfile` to build a container that will run the site for you if you have [Docker](https://www.docker.com/) installed.

Start by build the container:

```bash
docker build -t jekyll-site .
```

Next, run the container:
```bash
docker run -p 4000:4000 --rm -v $(pwd):/usr/src/app jekyll-site
```
## References

https://pages.github.com/

https://academicpages.github.io/

https://sites.google.com/view/vishal-ahuja/teaching?authuser=0

https://jiyong-park.github.io/about/ 

## Git commands

cd /Users/46773437/Library/CloudStorage/Dropbox/Data/01_research 
git clone https://github.com/kartechbabu/kartechbabu.github.io
git 
pwd


git add --all
git commit -m "Initial commit"
git push -u origin main
git branch
git push -u origin master
git commit -m "Initial commit"

git add --all
git push -u origin master
git commit -m "Initial commit"


git config --global user.name "Karthik Kannan"
git config --global user.email "kb.j2ee@gmail.com"

git commit -m "first version of website"