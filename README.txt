Github widget field

The Github widget field module provides a simple field that allows you to add a
Github repository to a content type, user, or any entity.

Display types include:

 * github_widget_jquery_formatter.
 * github_widget_simple_text.

Requirements: 
	-field_ui
	-Libraries
	-GitHub-jQuery-Repo-Widget by Joel Sutherland https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget
	
Instalation:
	-Download master branch from https://github.com/kpicaza/github_widget and unpack contents in libraries folder  sites/all/libraries/jquery.githubrepo
	
	-Follow the standard contributed module installation process:
http://drupal.org/documentation/install/modules-themes/modules-7
	
	-or-
	
	-unpack it to your Drupal /sites/all/modules directory
	-# drush -y en github_widget_field	

Usage:
	-To use this module, go to strycture/content_types & create a new field of type 'Github repository widget'. This field will
accept Github URLs path of the following format:

 * username/repositoryname


