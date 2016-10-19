#<b>Steps to Push or Host your First Heroku App</b>


##Open Command Prompt and Start Typing 

$mkdirgitrep<br>
$cd gitrepo<br>

$gitrepo><b>heroku login</b><br>
Enter your Heroku credentials.<br><br><br><br>
Email: xyzabc@gmail.com<br>
Password (typing will be hidden):<br>
Logged in as xyzabc@gmail.com<br><br>

$gitrepo><b>git clone git://github.com/MDShahrouq/helloworld.git<b><br><br>




Cloning into 'helloworld'...<br>
remote: Counting objects: 96, done.<br>
remote: Compressing objects: 100% (53/53), done.<br>
rRemote: Total 96 (delta 34), reused 96 (delta 34), pack-reused 0eceiving objects:<br>
Receiving objects:  66% (64/96)<br>
Receiving objects: 100% (96/96), 11.42 KiB | 0 bytes/s, done.<br>
Resolving deltas: 100% (34/34), done<br>
Checking connectivity... done.<br>




<br><br>$gitrepo><b>cd helloworld</b><br><br>

$gitrepo\helloworld><b>git status</b><br><br>

On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean

<br><br>$gitrepo\helloworld><b>heroku create</b><br><br>

Creating app... done, frozen-brushlands-67598<br>
https://frozen-brushlands-67598.herokuapp.com/ | https://git.heroku.com/frozen-brush<br>
lands-67598.git<br>

$gitrepo\helloworld>git remote -v<br>

heroku  https://git.heroku.com/frozen-brushlands-67598.git (fetch)<br>
heroku  https://git.heroku.com/frozen-brushlands-67598.git (push)<br>
origin  git://github.com/udacity/galeria.git (fetch)<br>
origin  git://github.com/udacity/galeria.git (push)

<br><br>$gitrepo\helloworld><b>git push heroku master</b><br><br>

Counting objects: 16, done.
Delta compression using up to 2 threads.
Compressing objects: 100% (12/12), done.
Writing objects: 100% (16/16), 2.59 KiB | 0 bytes/s, done.
Total 16 (delta 0), reused 15 (delta 0)
remote: Compressing source files... done.
remote: Building source:
remote:
remote: -----> Ruby app detected
remote: -----> Compiling Ruby/Rack
remote: -----> Using Ruby version: ruby-2.2.4
remote: -----> Installing dependencies using bundler 1.11.2
remote:        Running: bundle install --without development:test --path vendor/bund
le --binstubs vendor/bundle/bin -j4 --deployment
remote:        Fetching gem metadata from https://rubygems.org/..........
remote:        Fetching version metadata from https://rubygems.org/..
remote:        Using bundler 1.11.2
remote:        Installing tilt 2.0.2
remote:        Installing rack 1.6.4
remote:        Installing rack-protection 1.5.3
remote:        Installing sinatra 1.4.7
remote:        Bundle complete! 1 Gemfile dependency, 5 gems now installed.
remote:        Gems in the groups development and test were not installed.
remote:        Bundled gems are installed into ./vendor/bundle.
remote:        Bundle completed (2.29s)
remote:        Cleaning up the bundler cache.
remote:
remote: ###### WARNING:
remote:        You have not declared a Ruby version in your Gemfile.
remote:        To set your Ruby version add this line to your Gemfile:
remote:        ruby '2.2.4'
remote:        # See https://devcenter.heroku.com/articles/ruby-versions for more in
formation.
remote:
remote: -----> Discovering process types
remote:        Procfile declares types     -> web
remote:        Default types for buildpack -> console, rake
remote:
remote: -----> Compressing...
remote:        Done: 16.8M
remote: -----> Launching...
remote:        Released v4
remote:        https://frozen-brushlands-67598.herokuapp.com/ deployed to Heroku
remote:
remote: Verifying deploy... done.
To https://git.heroku.com/frozen-brushlands-67598.git
 * [new branch]      master -> master

C:\Users\MDShahrouq\gitrepo\galeria>heroku open

C:\Users\MDShahrouq\gitrepo\galeria>heroku apps:rename mdsrk
Renaming frozen-brushlands-67598 to mdsrk... done
https://mdsrk.herokuapp.com/ | https://git.heroku.com/mdsrk.git
Git remote heroku updated
 !    Don't forget to update git remotes for all other local checkouts of the app.

