# gov-repos

A simple way to access all the GitHub repos of US federal agencies.

Gem install or add to your Gemfile: `gov-repos`

```ruby

require 'gov-repos'

repos = GovRepos.new.get_repos

```

## Contributing to gov-repos
 
* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it
* Fork the project
* Start a feature/bugfix branch
* Commit and push until you are happy with your contribution
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

*Note: By contributing to this project, you agree to license your work under the same terms as those that govern this project's distribution.*

## Copyright ##

Copyright (c) 2012 Alan deLevie. See LICENSE.txt for further details.

