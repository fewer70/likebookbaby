# neo-ruby
Ruby Node and SDK for the NEO blockchain.

[![Build Status](https://travis-ci.org/blueplanet/neo_ruby.svg?branch=master)](https://travis-ci.org/blueplanet/neo_ruby) [![Coverage Status](https://coveralls.io/repos/github/blueplanet/neo_ruby/badge.svg?branch=master)](https://coveralls.io/github/blueplanet/neo_ruby?branch=master)

## TODO
- [ ] Run a ruby based P2P node
  - [ ] P2P communication
  - [ ] Save blockchain data to leveldb
- [ ] Interactive CLI for configuring node and inspecting block chain
- [ ] Runs smart contracts on the block chain in a ruby virtual machine

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/blueplanet/neo_ruby.
