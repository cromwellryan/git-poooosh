# .oh-my-zsh Plugin for helpful git pushing

## Installation

```shell
cd $ZSH/custom/plugins
git clone https://github.com/cromwellryan/git-poooosh.git
```

Activate the plugin by adding `git-poooosh` to the plugins
list in your `~/.zshrc` file.

```shell
plugins=(git-poooosh)
```

## Usage

```
$> git merge feature-branch
Updating 8ce1554..57de5d8
Fast-forward
 README.md | 1 -
 1 file changed, 1 deletion(-)

$> git-poooosh feature-branch

Total 0 (delta 0), reused 0 (delta 0)
To github.com:cromwellryan/git-pooosh.git
   8ce1554..57de5d8  master -> master
To github.com:cromwellryan/git-pooosh.git
 - [deleted]         feature-branch
Deleted branch feature-branch (was 57de5d8).

```

👌 Pro Tip: `alias gpp=git-poooosh`


![](http://g.recordit.co/mKiLTeRpVo.gif)
