# Carothar 5e

Carothar 5e is an open source D&D character management tool in the form of a web server.

Based largely in Go and in the Echo web server library. Any help is welcome! Check out Dev and Todo sections down below.

# Dev

### Web Routes

- /: Home page/help pages
  - /help/: Help pages when needed.
  - /app/: Interactive Character management part of the site.
  - /api/: Where data is gathered and changed.
  - /info/: D&D information API.

### Files

- src/: Code source
  - main.go: Wraps everything in a nice bow. Edit routes and handlers here.
  - server/: Server functionality written in Go.
  - static/: Static files sourced from root / link. Used for information pages and home page.
  - app/: Sourced from /app/ link. These are the web pages and javascript libraries that include the interactive parts. 
  - api/: Sourced from /api/ link. Files for authentification and the API.
  - info/: More statically served information. D&D API sourced here.

### Todo

- [ ] Static site home and help pages
- [ ] CSS style guide and styles
- [ ] Functionality
  - [ ] Data persistence
  - [ ] Backend API
    - [ ] Authentification
    - [ ] Data changing and sharing
    - [ ] Format for character data

## Progress Log

