require 'compass-rails'
require 'bootstrap-sass'
guard 'sass',
  :input => 'app/stylesheets',
  :output => 'public/stylesheets/compiled',
  :compass => {
    :project_type => :rails,
    :http_path => "/",
    :relative_assets => true,
    :css_dir => "public/stylesheets/compiled",
    :cache_dir => "/tmp/sassc",
    :sass_dir => "app/stylesheets",
    :images_dir => "public/images",
    :images_path => (File.join File.dirname(__FILE__),'public','images' ),
    :javascripts_dir => "public/javascripts",
    :http_images_path => "/images",
    :http_stylesheets_path => "/stylesheets",
    :http_javascripts_path => "/javascripts",
    :output_style => (:environment == :production) ? :compressed : :nested
  }
