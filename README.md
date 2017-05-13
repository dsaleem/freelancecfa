# Freelance Term2 Final Project

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
use SQLlite 3 for development test only
use PG for development production only


$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```



