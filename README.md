# SpreeWithExtensions
SpreeWithExtensions

Prerequsites:
*  Ruby: 2.2.1
*  postgresql

Make sure you run these commands once you checkout the github project.

*  bundle install
*  rake db:drop [if you have a db already by the name in the config/database.yml file]
*  rake db:create
*  rake db:migrate RAILS_ENV=development
*  rake db:seed
*  rake spree_sample:load
 
