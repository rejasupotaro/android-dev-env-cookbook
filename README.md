# Usage

```
$ git clone git@github.com:rejasupotaro/android-dev-env.git
$ cd android-dev-env
$ vim cookbooks/android-sdk/attributes/default.rb
...
$ gem install chef
$ chef-solo -c solo.rb -j nodes/localhost.json
```
