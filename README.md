# Setting Up Directory with Ruby / Jekyll
- Locate the file location
- In terminal run *bundle init*
- In the Gem File add gems that you want to use with *gem 'jekyll', '~> 4.3', '>= 4.3.1'*
- Once Gems are added run *bundle install*
- Once all that is done and ready use *bundle exec jekyll serve* (The server will run on port 4000)
- Load up *http://localhost:4000/* to see all the changes being made

# Using Browser Sync with Jekyll
- Run in termianl *npm init*
- Run in terminal *npm install --save-dev browser-sync* or globally with *npm install -g browser-sync*
- Add to the Gen File *gem 'jekyll-browsersync', group: [:jekyll_plugins]*
- Rerun the *bundle install* in terminal
- This command withh run the server with browser Sync on *bundle exec jekyll browsersync*
- Load up *http://localhost:4000/* to see all the changes being made
