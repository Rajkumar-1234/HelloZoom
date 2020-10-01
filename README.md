# HelloZoom
An attempt to make a Zoom prototype.
A whole bunch of new features will also be implemented as soon as possible!

## Install to Heroku
Hello supports Heroku as a demonstration platform. Deployment can be done via the one-click [Deploy to Heroku](https://heroku.com/deploy?template=https://github.com/itss1ddhant/Hello) button or the commands below:

```
heroku login
git clone https://github.com/itss1ddhant/HelloZoom.git
cd hellozoom
git push heroku master
heroku ps:scale web=1
heroku open
heroku logs --tail
```
