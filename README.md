# Local Farmware Server

A server that runs on `localhost:4567` and serves two files:

 * `manifest.json` - The Farmware manifest
 * `farmware.zip` - The Farmware bundle

# Pro Tips

 * Editing `main.py` updates the farmware.
 * Editing `manifest.json` will override defaults
 * Visiting `http://localhost:4567/manifest.json` loads manifest.
 * Visiting `http://localhost:4567/farmware.zip` loads farmware.
 * Visiting `http://localhost:4567/` provides a link to both.

# Install

```
git clone THIS_REPO
cd THIS_REPO
bundle install
touch main.py
touch manifest.json
```

# Run

Run server:

```
ruby main.rb
```

Then:

 * Edit `main.py`
 * Use `http://localhost:4567/manifest.json` like normal.
