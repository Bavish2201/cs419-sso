# Single Sign On

The site is live at https://bavish2201.github.io/cs419-sso/

## Installation

### Install Jekyll

[Jekyll](https://jekyllrb.com/docs/installation/windows/)

```
sudo apt-get update -y && sudo apt-get upgrade -y

sudo apt-add-repository ppa:brightbox/ruby-ng 
sudo apt-get update 
sudo apt-get install ruby2.5 ruby2.5-dev build-essential dh-autoreconf
gem update
gem install jekyll bundler

```
### Clone the Repository
```
git clone https://github.com/Bavish2201/cs419-sso.git
cd cs419-sso
```
### Running locally

```
bundle exec jekyll serve --config _local_config.yml
```
If it gives some error, try running the following and then run the above command
```
bundle update
bundle install
```
## Adding Content
All the content files should be added to the `docs` folder. There are two sample files `intro.md` and `security.md` provided. Delete these and create more files in the same format. The number in the `nav_order` field is the location of the file in the navigation bar. Set this number appropriately.

For more info on navigation, see [this](https://pmarsceill.github.io/just-the-docs/docs/navigation-structure/).