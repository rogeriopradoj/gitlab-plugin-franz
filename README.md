# gitlab-plugin-franz
GitLab plugin for [Franz]()

## Installing

### via git clone

1. In your terminal, change to Plugins directory:
  * Mac: `cd ~/Library/Application Support/Franz/Plugins/`
  * Windows: `cd %appdata%/Franz/Plugins`
  * Linux: `cd ~/.config/Franz/Plugins`

2. Git clone this repository:
```
$ git clone https://github.com/rogeriopradoj/gitlab-plugin-franz.git gitlab
```

3. Restart Franz.


### via zip downloading

1. [Download zip](https://github.com/rogeriopradoj/gitlab-plugin-franz/archive/master.zip), extract it and move the folder gitlab into Plugins directory:
  * Mac: `~/Library/Application Support/Franz/Plugins/`
  * Windows: `%appdata%/Franz/Plugins`
  * Linux: `~/.config/Franz/Plugins`

2. Restart Franz.


## Updating

### via git clone

If your installation is via git clone, you can update it via git pull:
```
$ git pull origin master
```

### via zip re-downloading

If your installation is via zip downloading, you can update it deleting the gitlab plugin folder and [re-downloading the plugin](#via-zip-downloading).

## Contributing

That's awesome you want to contribute with this project. Here's a summary of what you need to start with it (borrowed from the great article <https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/>):

* Fork the project & clone locally.
* Create an *upstream* remote and sync your local copy before you branch.
* Branch for each separate piece of work.
* Do the work, write [good commit messages](https://blogs.gnome.org/danni/2011/10/25/a-guide-to-writing-git-commit-messages/), and read the CONTRIBUTING file if there is one.
* Push to your *origin* repository.
* Create a new PR in GitHub.
* Respond to any [code review](http://lornajane.net/posts/2015/code-reviews-before-you-even-run-the-code) feedback.

## Maintainer

- [Rogerio Prado de Jesus](https://rogeriopradoj.com/about) - [@RogerioPradoJ](https://twitter.com/rogeriopradoj)

## License

- [MIT](LICENSE)