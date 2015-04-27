# closeio-hipchat-addon
A HipChat add-on to give details about a Close.io lead when its URL is mentioned in HipChat

## One-time setup
    # Download the repository.
    git clone https://github.com/elasticsales/closeio-hipchat-addon.git
    cd closeio-hipchat-addon

    # Create new heroku application
    heroku create closeio-hipchat-addon

    # Attach PostgreSQL to an application
    heroku addons:add heroku-postgresql

    # Set your addons URL
    heroku config:set HIPCHAT_ADDON_BASE_URL="https://closeio-hipchat-addon.herokuapp.com"

    # Deploy it
    git push heroku master

Now, you're ready to install the add-on.

## Additional deployments
    git push heroku master

## Usage
Once the app is running on a server, then a HipChat admin can go to:

Integrations > Manage > Install an integration from a descriptor URL

Or, get HipChat to list your integration in their overall integrations page and install from there.

