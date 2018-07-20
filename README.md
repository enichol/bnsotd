# README

## Steps to get this thing going 

1. install [hexo](https://hexo.io/docs/index.html)
2. install [git](https://git-scm.com/downloads)
3. pull [repo](https://github.com/enichol/bnsotd.git)
4. cd into /bnsotd/ repo
5. pull forked theme: `git clone https://github.com/enichol/hexo-theme-cactus.git themes/cactus`


## to run locally:

1. `hexo clean`
2. `hexo generate`
3. `hexo server`
4. Navigate to http://localhost:4000 in your browser

## To generate a new post:
1. `hexo new [title]`
2. Edit  /source/\_posts/_[title]_.md (copy an existing post as a template)
3. Dump the audio file in /source/_posts/_title_
4. `hexo generate` and `hexo server` again to see changes

## To deploy:

1. get [awscli](https://docs.aws.amazon.com/cli/latest/userguide/installing.html)
2. run `aws configuration`  and enter the bnsotd:
    * access key
    * secret key, 
    * region (us-east-1) 
    * and some fourth thing
