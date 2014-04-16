# Arca Android Templates

These templates are to be used in conjunction with the [arca android](https://github.com/cfmobile/arca-android) library and the [levo](https://github.com/cfmobile/levo) templating engine.

Try running the following commands to see them in action:

```mkdir android && cd android```

```levo -k com.my.package -p MyProject -t github.com/cfmobile/arca-android-templates -m "User id:long name:string age:int";```

```cd ..```

```mkdir rails && cd rails```

```levo -k com.my.package -p MyProject -t github.com/cfmobile/rails-scaffold-templates -m "User id:long name:string age:int";```

```rails new my_project -m my_project.rb;```

```cd my_project && rails s;```

Next go to `localhost:3030/users` and add a few sample users.

Finally load up your android application and watch it fetch your user list. 

## Features

From the command line the following features are supported with the `-f` flag.

#### sync

When enabled, the sync feature will scaffold all the files necessary to implement a sync adapter within your application.
