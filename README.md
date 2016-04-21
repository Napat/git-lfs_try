# git-lft_try
Try git-lfs

1.Get git-lfs client from https://git-lfs.github.com and first settup with
$ git lfs install

2.Go to repository and manage extemsions(or manual edit .gitattributes)
$ git lfs track "*.jpg"
$ git add .gitattributes
$ git commit -a -m "git lfs filterring all *.jpg files"

3.Feel free to Add/commit/push to github like normally
$ git add img/napat1.jpg
$ git commit -m "Add new image"
$ git push origin master

More commands
$ git lfs track
$ git lfs ls-files
