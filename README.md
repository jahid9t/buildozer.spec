[app]

# (str) Title of your application
title = ShadowApp

# (str) Package name
package.name = shadow

# (str) Package domain (unique reverse domain name, like org.yourname.app)
package.domain = org.shadow

# (str) Source code where main.py is located
source.dir = .

# (str) File extensions to include
source.include_exts = py,png,jpg,kv,atlas

# (str) Application versioning
version = 1.0

# (list) Application requirements
requirements = python3,kivy

# (str) Orientation of the app (portrait or landscape)
orientation = portrait

# (bool) Fullscreen mode
fullscreen = 1

# (list) Permissions needed for your app
android.permissions = INTERNET

# (bool) Hide the statusbar (1 = yes, 0 = no)
android.hide_statusbar = 1

# (str) The entry point for your app (main.py)
entrypoint = main.py

# (str) Supported Android API level (33 is latest stable)
android.api = 33

# (str) Minimum Android API version your app supports
android.minapi = 21

# (bool) Use androidX (needed for recent APIs)
android.enable_androidx = 1

# (str) Name of the .apk file (optional)
android.archive_name = shadow

[buildozer]

# (int) Log level (0 = error only, 2 = debug)
log_level = 2

# (bool) Warn when building as root (not recommended)
warn_on_root = 1
