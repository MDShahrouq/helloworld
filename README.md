#<b>Steps to Deploy your Web Application with Heroku </b>

###Prerequisite are as Follows with their Apporpriate Links::<br><br>
* Heroku Account https://www.heroku.com<br>
* Heroku Toolbelt https://toolbelt.heroku.com<br>
* Git Installed https://git-scm.com/book/en/v2/Getting-Started-Installing-Git



<br>
##Open Command Prompt and Start Typing <br>

$mkdir gitrepo<br>
$cd gitrepo<br>

$gitrepo><b>heroku login</b><br>
Enter your Heroku credentials.<br>
Email: xyzabc@gmail.com<br>
Password (typing will be hidden):<br>
Logged in as xyzabc@gmail.com<br><br>

$gitrepo><b>git clone git://github.com/MDShahrouq/helloworld.git</b><br>

Cloning into 'helloworld'...<br>
remote: Counting objects: 96, done.<br>
remote: Compressing objects: 100% (53/53), done.<br>
rRemote: Total 96 (delta 34), reused 96 (delta 34), pack-reused 0eceiving objects:<br>
Receiving objects:  66% (64/96)<br>
Receiving objects: 100% (96/96), 11.42 KiB | 0 bytes/s, done.<br>
Resolving deltas: 100% (34/34), done<br>
Checking connectivity... done.<br>


<br>$gitrepo><b>cd helloworld</b><br><br>

$gitrepo\helloworld><b>git status</b><br><br>

On branch master<br>
Your branch is up-to-date with 'origin/master'.<br>
nothing to commit, working tree clean

<br><br>$gitrepo\helloworld><b>heroku create</b><br><br>

Creating app... done, frozen-brushlands-67598<br>
https://frozen-brushlands-67598.herokuapp.com/ | https://git.heroku.com/frozen-brush<br>
lands-67598.git<br><br>

$gitrepo\helloworld><b>git remote -v</b><br>

heroku  https://git.heroku.com/frozen-brushlands-67598.git (fetch)<br>
heroku  https://git.heroku.com/frozen-brushlands-67598.git (push)<br>
origin  git://github.com/udacity/galeria.git (fetch)<br>
origin  git://github.com/udacity/galeria.git (push)

<br><br>$gitrepo\helloworld><b>git push heroku master</b><br><br>

Counting objects: 16, done.<br>
Delta compression using up to 2 threads.<br>
Compressing objects: 100% (12/12), done.<br>
Writing objects: 100% (16/16), 2.59 KiB | 0 bytes/s, done.<br>
Total 16 (delta 0), reused 15 (delta 0)<br>
remote: Compressing source files... done.<br>
remote: Building source:<br>
remote:<br>
remote: -----> Ruby app detected<br>
remote: -----> Compiling Ruby/Rack<br>
remote: -----> Using Ruby version: ruby-2.2.4<br>
remote: -----> Installing dependencies using bundler 1.11.2<br>
remote:        Running: bundle install --without development:test --path vendor/bund
le --binstubs vendor/bundle/bin -j4 --deployment<br>
remote:        Fetching gem metadata from https://rubygems.org/..........<br>
remote:        Fetching version metadata from https://rubygems.org/..<br>
remote:        Using bundler 1.11.2<br>
remote:        Installing tilt 2.0.2<br>
remote:        Installing rack 1.6.4<br>
remote:        Installing rack-protection 1.5.3<br>
remote:        Installing sinatra 1.4.7<br>
remote:        Bundle complete! 1 Gemfile dependency, 5 gems now installed.<br>
remote:        Gems in the groups development and test were not installed.<br>
remote:        Bundled gems are installed into ./vendor/bundle.<br>
remote:        Bundle completed (2.29s)<br>
remote:        Cleaning up the bundler cache.<br>
remote:<br>
remote: ###### WARNING:<br>
remote:        You have not declared a Ruby version in your Gemfile.<br>
remote:        To set your Ruby version add this line to your Gemfile:<br>
remote:        ruby '2.2.4'<br>
remote:        # See https://devcenter.heroku.com/articles/ruby-versions for more in<br>
formation.<br>
remote:<br>
remote: -----> Discovering process types<br>
remote:        Procfile declares types     -> web<br>
remote:        Default types for buildpack -> console, rake<br>
remote:<br>
remote: -----> Compressing...<br>
remote:        Done: 16.8M<br>
remote: -----> Launching...<br>
remote:        Released v4<br>
remote:        https://frozen-brushlands-67598.herokuapp.com/ deployed to Heroku<br>
remote:<br>
remote: Verifying deploy... done.<br>
To https://git.heroku.com/frozen-brushlands-67598.git<br>
 * [new branch]      master -> master<br>
<br>
$gitrepo\helloworld><b>heroku open</b><br><br>

<b> :+1:Congratulation! You Did It </b>
<i>Feel Free to Contact me:</i>
<br>Email:<b>mdshahrouq@gmail.com</b><br>
Linkedin:<b>https://www.linkedin.com/in/mdshahrouq</b><br>
