# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions


# INSIRA AS SEGUINTES LINHAS NO SEU GEM FILE

	* gem 'sprockets-rails', '~> 3.2', '>= 3.2.1'
	* gem 'bootstrap', '~> 4.1.1'
	* gem 'jquery-rails'
	* gem 'autoprefixer-rails'

# BUNDLE
	
	* na raiz da sua aplicação execute: bundle install

# REALIZE AS CONFIGURAÇÕES 

	* mv app/assets/stylesheets/application.css app/assets/stylesheets/application.scss

# NO ARQUIVO APPLICATION.SCSS

	* remova as linhas "*= require" e "*= require_tree"
	* no fim do arquivo adicione: @import "bootstrap";

# NO ARQUIVO APPLICATION.JS

	* A ordem das linhas é muito importante

	//= require jquery3
	//= require rails-ujs
	//= require activestorage
	//= require turbolinks
	//= require popper
	//= require bootstrap-sprockets
	//= require_tree .

