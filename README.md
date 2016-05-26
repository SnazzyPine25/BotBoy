# BotBoy
A big bundle of API stuff and image generators.

## How to run
You need Ruby 2.3, Bundler and ImageMagick.
You can download ImageMagick from [http://www.imagemagick.org/](http://www.imagemagick.org/) or, if you are on Ubuntu, you can easily running this command:
```
sudo apt-get install libmagickwand-dev
```
First, install all the dependencies using `bundle install`. Then edit the file "bb-auth" to this format:
```
TOKEN HERE
171456123456123456
```
Then, use `ruby botboy.rb` to run it.

## Settings and Configuration
### If you want Mention Prefixes:
In the file `botboy.rb`, simply replace `USER_ID` with the bots User ID.

### If you want to change source code settings:
You can set them all after line 28.

### If you want to use the eval command:
Replaye with your ID in line 551 in the source code.

## Things I really need help with.
  * Masking in dis-card commands. `Line 114-442`
  * Better way to customize settings.
  * Requesting in mcserv command. `Line 98-112`
  * Fallback to commands.
  * A lighter script.
  * A better meme command handler `Line 460-475`
  * Unbug cat command `Line 447-513`