# RailsCasts Episode #376: JRuby on Rails

http://railscasts.com/episodes/376-jruby-on-rails

Requires Ruby 1.9.2 or higher.


### Commands used in this episode

```
rbenv install jruby-1.7.0-preview2
rbenv shell jruby-1.7.0-preview2
ruby -v
jruby -v
jirb
irb
ruby swing.rb
ruby fib.rb
rbenv shell 1.9.3-p194
ruby fib.rb
rbenv shell jruby-1.7.0-preview2
gem install rails
# or jruby -S gem install rails
rails new blog
gem install sqlite3
rails g scaffold article name
rake db:migrate
rails s
time (rails runner nil)
```

### Commands used in irb

```
h = java.util.HashMap.new
h.put(:foo, "bar")
h.get(:foo)
h[:foo]
h.java_class
javax.swing.JOptionPane.showMessageDialog(nil, "Hello World!")
Java::JavaxSwing::JOptionPane.show_message_dialog(nil, "Hello World!")
```
