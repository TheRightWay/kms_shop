# KMS Shop
Extends KMS Catalog by adding cart and orders feature.

## Installation

1. Add to Gemfile

        gem "kms_shop"
        # or for edge version:
        gem "kms_shop", github: "webgradus/kms_shop"

2. Run generator:

        bundle exec rails g kms_shop:install

3. Copy migrations:

        bundle exec rails kms_shop:install:migrations

4. Migrate:

        bundle exec rails db:migrate

5. Recompile assets (if on production):

        bundle exec rails assets:precompile

6. Restart KMS instance

## Contributing

Please follow [CONTRIBUTING.md](CONTRIBUTING.md).

## License
The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).