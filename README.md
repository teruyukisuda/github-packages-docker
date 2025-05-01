# リリース
* 手動リリース
```aiignore
gh workflow run publish.yml -f version=0.1.0
```
* tagをpushしてリリース
```aiignore
$ git tag v0.1.0
$ git push && git push --tags
```
* 成果物は、[ここ](https://github.com/teruyukisuda/github-packages-docker/pkgs/container/gha-image)
