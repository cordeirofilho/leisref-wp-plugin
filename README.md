LeisRef plugin for WordPress
========================

## Introduction

This plugin creates a search interface for the [Virtual Health Library](http://modelo.bvsalud.org/en/) Legislation information source.

## Requirements

Wordpress 3.x

## Install

0. [Download](https://github.com/bireme/leisref-wp-plugin/archive/master.zip) the LeisRef plugin for Wordpress;
0. Unzip the plugin below the `wp-content/plugins` folder of your Wordpress instance and rename it to `leisref`;
0. Activate the LeisRef plugin through the administration panel of WordPress (dashboard).

For further information on installing plugins please see the [Manual Plugin Installation from Wordpress codex site](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

## Configuration

Go to `Settings` in the administration panel (dashboard) and click on the newly created `LeisRef` item.
* `Plugin page` is mandatory and is set to `legislation` by default. It defines the URL of the search interface page;
* `Filter query` is optional and defines the strategy (a term or expression) to act as a filter for record displaying.
* `Search form` is optional and defines a flag to control the display of the search box in the homepage;
* `AddThis profile ID` is optional and is provided to allow the integration with sharing tools services [AddThis](http://www.addthis.com/). Notice this requires previous registration within the sharing tools service;
* `Google Analytics code` is optional and allows the integration of website analytics services provided by Google. Notice this requires previous registration in Google.
