If you follow these contributing guidelines your patch
will likely make it into a release a little quicker.


## Contributing

1. Fork the repo.

2. Create your feature branch (`git checkout -b feature/my-new-feature`)

3. Run the tests. We only take pull requests with passing tests, and
   it's great to know that you have a clean slate

4. Add a test for your change. Only refactoring and documentation
   changes require no new tests. If you are adding functionality
   or fixing a bug, please add a test.

5. Make the test pass.

6. Push to your fork and submit a pull request.


## Dependencies

All dependencies are listed in Puppetfile

## Syntax and style

There is integrated link task in Rakefile that depends on metadata-json-lint to lint metadata.json

## Running the unit tests

To run tests suits you need to have `bundler`. To install all necessary gems use `bundle install` in root folder of project.

To see available test tasks use: `bundle exec rake -T`.  

## Integration tests
Integration tests are made with `beaker` and `vagrant`.
