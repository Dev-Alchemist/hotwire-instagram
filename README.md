# Instagram Clone
This is a simple Instagram clone project built with Ruby on Rails 7, Hotwire, and Tailwind CSS. It allows users to sign up, log in, upload images, like and unlike posts, comment on posts, and like and unlike comments. It uses Devise for authentication and Active Storage for image upload.

## Prerequisites
* Ruby 3.1.3
* Rails 7
* PostgreSQL
* Redis

Installation
1. Clone the repository to your local machine:
```bash
git clone git@github.com:your_username/instagram-clone.git
```
2. Change directory to the project folder:
```bash
cd instagram-clone
```
3. Install the required gems:
```bash
bundle install
```
4. Setup the database >> You can check the `` bin/setup`` file.
```bash
bin/rails db:prepare
```
5. Start the project:
```bash
# run this on a separate terminal instance
redis-server 
#also run this on a separate instance
bin/dev
```
6. Visit http://localhost:3000 in your browser to view the application.

## Features
Authentication
Users can sign up and log in to the application using Devise.

## Image Upload
Users can upload images to the application using Active Storage.

## Like and Unlike Posts
Users can like and unlike posts by clicking the heart icon.

## Comment on Posts
Users can comment on posts by typing their comment in the comment box and clicking the "Comment" button.

## Future Improvements
One of the TODOs for this project is to use polymorphic associations for the comments and likes table. This will allow for more flexibility and scalability in the future.