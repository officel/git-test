# git-test

## Keybase with GPG on Github

### links

* https://keybase.io/
* https://keybase.io/docs
* https://www.gpg4win.org/


### history

```
mkdir git-test
cd git-test/
echo "# git-test" >> README.md
git init
git add README.md

git config user.email "**********@gmail.com"
git config user.name "raki"
git config user.signingkey 24F3D086CB58D89E
git config commit.gpgsign true
git config --global gpg.program "path/to/gpg"

git commit -m "first commit"
git remote add origin git@github.com:officel/git-test.git
git push -u origin master
```

* PGP Keyがおいてあるとことを意識しないとしくじる

