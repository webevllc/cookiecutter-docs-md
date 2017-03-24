# cookiecutter-git
**Git Cookiecutter**. Git Repository Project Template!

## Features
- [Bare project structure](https://github.com/webevllc/example-repo)
- [License customization](https://developer.github.com/v3/licenses/)
- [Gitignore customization](https://www.gitignore.io/)
- Remote repository creation
  - [GitHub.com as provider](https://github.com/)
  - [GitLab.com as provider](https://gitlab.com/)
- Cross-platform support

### Upcoming
- [Bitbucket.org support](https://bitbucket.org/)
- Full coverage testing
- Continuous integration
- First tagged release
- Add [logging](https://docs.python.org/2/library/logging.html) to hooks ?
- [CodeCommit support](https://aws.amazon.com/codecommit/) ?

## Requirements
- [git](https://git-scm.com/downloads)
- [python](https://www.python.org/downloads/)
- [cookiecutter](https://github.com/audreyr/cookiecutter)

## Usage
    $ cookiecutter gh:webevllc/cookiecutter-git

### Example
See [example-repo](https://github.com/webevllc/example-repo)

    $ tree -a test-repo
    test-repo
    ├── AUTHORS.md
    ├── CHANGELOG.md
    ├── CONTRIBUTING.md
    ├── .git
    ├── .gitignore
    ├── LICENSE
    ├── NOTICE
    ├── README.md
    └── test_pkg
        └── .gitkeep

    2 directories, 8 files

## Resources
- [Gitignore Docs](https://www.gitignore.io/docs)
- [GitHub Repos API](https://developer.github.com/v3/repos/)
- [GitLab Projects API](https://docs.gitlab.com/ce/api/projects.html)

## Development
See [CONTRIBUTING](CONTRIBUTING.md)

## History
See [CHANGELOG](CHANGELOG.md)

## Credits
See [AUTHORS](AUTHORS.md)

## License
See [LICENSE](LICENSE), [NOTICE](NOTICE)
