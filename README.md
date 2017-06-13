exclamation: RubyMon is currently in Pre-alpha stage.

# RubyMon
RubyMon automatically reruns your ruby file when changes are made. Simply switch to your working directory and type 'rubymon' into the command line. To explicitly listen to a single file use: 'rubymon file'.
## Features
* You don't have to exit your running ruby file manually. After saving your modified file, RubyMon will automatically run the modified ruby file without You having to take care of it. (very useful for bots)
## Installation
You can simply install - and run - RubyMon using the command line (for example: Windows PowerShell).
```ruby
gem install rubymon #To install the latest version of rubymon - recommended
```

Gem dependencies: <a href="https://github.com/guard/listen">Guard/listen</a>
In case of an error caused by <b>Guard/listen</b> I take no responsibility. Report errors concerning <b>Guard/listen</b>: <a href="https://github.com/guard/listen/issues">Report issue</a> <b>(only errors caused by <i>Guard/listen</i>)</b>
## Usage
To run RubyMon, switch to your working directory and type 
```ruby
rubymon
```
into your command line. Whoola. It SHOULD work.


To **explicitly** listen to a single file in your directory use 
```ruby
rubymon file
```
and then follow the steps.
##Author
***RubyMon**
