# README

To get started, clone the repo and install needed gems:

bundle install --without production

Next, migrate the database:

rails db:migrate

Finally, run the test suite to verify that everything is working correctly:

rails test

If the test suite passes, you'll be able to run the app in a local server:

rails server
