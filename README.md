This is a temporary repo, and a sample static site for a course.

# List of steps in stupid detail

1. Install ruby (ruby-full build-essential zlib1g-dev)
2. Move gems installation to hidden folden in home and export path 
3. Install jekyll and bundler
4. Realize ruby in ubuntu repos is ancient. Install rbenv dependencies (curl autoconf bison build-essential libssl-dev libyaml-dev libreadline6-dev zlib1g-dev libncurses5-dev libffi-dev libgdbm6 libgdbm-dev libdb-dev )
5. Install rbenv (curl -fsSL https://github.com/rbenv/rbenv-installer/raw/HEAD/bin/rbenv-installer | bash) and add that to path
6. Install latest ruby and set it to global
7. Install jekyl,upgrade bundler and generate jekyll skeleton
8. Add github pages gem to gemfile (as per the comments in the original Gemfile) and ran bundle install
9. That gemfile broke the site I then ran commands that broke jekyll
10. Moved site to root after reinstalling the gems I wrongly removed. This version does not use the github pages gem
11. Followed instrictions in the gemfile and now it does not work locally. Trying pages

