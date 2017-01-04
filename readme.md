# Heroku Wrapper


## Environment
- **Rack**:  1.5.0
- **Vienna**

## Setup

### Place your project in the Public folder

 Make sure you place your assets in the folders as set up-- you can create your own asset folders, however you must treat the public folder as if it were the central location for all your code, as you'd typically lay it out

```
bundle install
```

### Run Server

```
bundle exec rackup
```
### Pushing To Heroku
Make sure your code is layed out in the public folder as you'd like to see it. Run a local server to test. Otherwise, push everything to heroku as-is and it should work right out of the box.
