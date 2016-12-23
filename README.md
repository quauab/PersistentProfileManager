# Profile Manager with Database Persistence

## A web application that manages user profiles, using CouchDB backend

``` bash
# Install Dependencies
With this existing package.json file:
  npm install
  
# External Dependencies
  CouchDB - http://couchdb.apache.org/

Without this existing package.json file:
  npm init
  npm install express body-parser consolidate dust dustjs dustjs-linkedin uuid chalk couch-db --save

# Install Nodemon
npm install -g nodemon

# Run Application
nodemon

## Changed
    # Issue: Newly added input data doesn't show on the edit modal from within the main page
    # Revised: Removed edit modal from the main page. Editing now takes place on the profile page
```
