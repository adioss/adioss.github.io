# adioss.github.io

Theme: https://themes.gohugo.io/hugo-theme-hello-friend/

```
docker run --rm -it -v $(pwd):/src klakegg/hugo:0.80.0 
docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:0.80.0 server
```

Remove submodules

```
Delete the relevant section from the .gitmodules file.
Stage the .gitmodules changes git add .gitmodules
Delete the relevant section from .git/config.
Run git rm --cached path_to_submodule (no trailing slash).
Run rm -rf .git/modules/path_to_submodule (no trailing slash).
Commit git commit -m "Removed submodule "
Delete the now untracked submodule files rm -rf path_to_submodule
```