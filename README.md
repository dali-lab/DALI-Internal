# DALI-internal

Apps and integrations built for lab use are included here as submodules.

# Contributing

## To clone all repositories
```bash
$ git clone --recursive https://github.com/dali-lab/DALI-internal.git
```

# To contribute a feature
1. Clone the relevant repository
2. Create a branch named `feature/<feature-name>`
3. Submit a pull request

More information on using [submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules) - submodules are a little bit tricky but the thing to remember is that the main repo points to specific commits of each submodule, thus to update you have to manually pull or `git submodule update --remote`, and often when you first check out you'll need to remember to switch to the `master` branch as well.
