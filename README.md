# SimpleForum
The goal of this project is to write an application where users can register, sign in and create threads on a forum where they can be replied to by other users.

## Cloning the project
If you want to clone the repository you'll need to do a few extra steps before you'll be able to run the project.

```bash
git clone git@github.com:king601/SimpleForum.git && cd SimpleForum/
cp config/secrets.yml.example config/secrets.yml
cp config/database.yml.example config/database.yml
rake db:create && rake db:migrate
```
Then you may start the rails development server with
```
rails server -p 3000
```
