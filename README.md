# Arca Android Templates

These templates are to be used in conjunction with the [arca android](https://github.com/cfmobile/arca-android) library and the [levo](https://github.com/cfmobile/levo) templating engine.

Try running the following commands to see them in action:

Create your android application:

```bash
mkdir android && cd android

levo -t github.com/cfmobile/arca-android-templates -m "User id:long name:string age:int"
```

If you don't yet have an api create a basic rails app:

```bash
mkdir rails && cd rails

levo -p MyProject -t github.com/cfmobile/rails-scaffold-templates -m "User id:long name:string age:int"

rails new my_project -m my_project.rb

cd my_project && rails s
```

Next go to `localhost:3000/users` and add a few sample users;

Finally load up your android application and watch it fetch your user list. 

## Features

From the command line the following features are supported with the `-f` flag.

#### sync

When enabled, the sync feature will scaffold all the files necessary to implement a sync adapter within your application.
