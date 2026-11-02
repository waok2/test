# Contributing

Thanks for helping out! To propose a change:

1. **Branch from `master`** (the default branch):
   `git checkout master && git pull && git checkout -b my-change`
2. **Keep changes small.** One focused change per branch is easier to
   review. Split larger work into several pull requests.
3. **Run the tests and linter** before pushing:
   `docker-compose run app sh -c "python manage.py test && flake8"`
4. **Open a pull request** against `master` with a short description of
   what changed and why.
