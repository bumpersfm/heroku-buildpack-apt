Installs the wavefront proxy on your heroku dyno.

Setup:

In heroku:
Enable dyno metadata: https://devcenter.heroku.com/articles/dyno-metadata
Set the $WAVEFRONT_SERVER variable to the Wavefront URL:" "https://try.wavefront.com/api/"
Set the $WAVEFRONT_TOKEN variable to the api token
Add the git url to this buildpack to your apps buildpacks. https://github.com/bumpersfm/wavefront-buildpack.git for example
