# This file manages Puppet module dependencies.
#
# It works a lot like Bundler. We provide some core modules by
# default. This ensures at least the ability to construct a basic
# environment.

def github(name, version, options = nil)
  options ||= {}
  options[:repo] ||= "boxen/puppet-#{name}"
  mod name, version, :github_tarball => options[:repo]
end

# Includes many of our custom types and providers, as well as global
# config. Required.

github "boxen", "1.2.0"

# Core modules for a basic development environment. You can replace
# some/most of these if you want, but it's not recommended.

github "dnsmasq",  		"1.0.0"
github "gcc",      		"1.0.0"
github "git",      		"1.0.0"
github "homebrew", 		"1.1.2"
github "hub",      		"1.0.0"
github "inifile",  		"0.9.0", :repo => "cprice-puppet/puppetlabs-inifile"
github "nginx",    		"1.1.0"
github "nodejs",   		"1.0.0"
github "nvm",      		"1.0.0"
github "ruby",     		"3.1.0"
github "stdlib",   		"3.0.0", :repo => "puppetlabs/puppetlabs-stdlib"
github "sudo",     		"1.0.0"
github "osx", 			"1.0.0"

github "alfred",   		"1.0.1"
github "wunderlist",    "1.0.0"
github "virtualbox", 	"1.0.1"
github "vagrant",		"2.0.3"
github "dropbox",		"1.1.0"
github "lastpass",         "1.0.0", :repo => "dieterdemeyer/puppet-lastpass"
github "sequel_pro",       "0.1.0", :repo => "todd/puppet-sequel_pro"

github "sublime_text_2","1.1.0"

github "chrome",	    "1.1.0"
github "firefox",	    "1.0.5"

github "iterm2", 		"1.0.2"
github "zsh",			"1.0.0"

github "spotify",  		"1.0.0"
github "vlc",	   		"1.0.0"

github "flux",	   		"0.0.1"
github "unarchiver",       "1.0.0", :repo => "dieterdemeyer/puppet-unarchiver"

# Optional/custom modules. There are tons available at
# https://github.com/boxen.
