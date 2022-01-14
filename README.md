# custom-terminal-splash-screen-ruby
Responsive Ruby Splash Screen of my terminal written in Ruby

![Demo Screen](./images/demo.png)

# How to run

1) First make sure you have Ruby installed, if you don't have it, run `sudo apt install ruby-full`
2) Install the following Dependences `sudo gem install colorize tty-screen`
3) `ruby splash.rb`

 # Edit it, add your name and logo

 You can edit and add your name and logo just editing the splash string. 

 # Set it up as splash screen of your terminal

 First copy splash.rb to your home folder with the following command: `cp splash.rb ~/.splash.rb`
 Edit your .bashrc or .zshrc and add to the last line `ruby .splash.rb`