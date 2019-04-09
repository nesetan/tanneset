# This is the default format.
# For more see: https://github.com/mojombo/jekyll/wiki/Permalinks
permalink: /:categories/:year/:month/:day/:title

exclude: [".rvmrc", ".rbenv-version", , "Rakefile", "changelog.md", , "Makefile", "Gemfile", "Gemfile.lock"]
highlighter: rouge

# Themes are encouraged to use these universal variables
# so be sure to set them if your theme uses them.
#
title : Karl Broman
author :
  name : Karl Broman
  email : kbroman@gmail.com
  github : kbroman
  twitter : kwbroman
  feedburner : nil

production_url : https://kbroman.github.io

# Tell Github to use the kramdown markdown interpreter
# (see https://help.github.com/articles/migrating-your-pages-site-from-maruku)
markdown: kramdown

# All Jekyll-Bootstrap specific configurations are namespaced into this hash
#
JB :
  version : 0.3.0

  # All links will be namespaced by BASE_PATH if defined.
  # Links in your website should always be prefixed with {{BASE_PATH}}
  # however this value will be dynamically changed depending on your deployment situation.
  #
  # CNAME (http://yourcustomdomain.com)
  #   DO NOT SET BASE_PATH
  #   (urls will be prefixed with "/" and work relatively)
  #
  # GitHub Pages (http://username.github.io)
  #   DO NOT SET BASE_PATH
  #   (urls will be prefixed with "/" and work relatively)
  #
  # GitHub Project Pages (http://username.github.io/project-name)
  #
  #   A GitHub Project site exists in the `gh-pages` branch of one of your repositories.
  #  REQUIRED! Set BASE_PATH to: http://username.github.io/project-name
  #
  # CAUTION:
  #   - When in Localhost, your site will run from root "/" regardless of BASE_PATH
  #   - Only the following values are falsy: ["", null, false]
  #   - When setting BASE_PATH it must be a valid url.
  #     This means always setting the protocol (http|https) or prefixing with "/"

  # By default, the asset_path is automatically defined relative to BASE_PATH plus the enabled theme.
  # ex: [BASE_PATH]/assets/themes/[THEME-NAME]
  #
  # Override this by defining an absolute path to assets here.
  # ex:
  #   http://s3.amazonaws.com/yoursite/themes/watermelon
  #   /assets
  #
  # ASSET_PATH : https://kbroman.org/assets/themes/twitter

  # These paths are to the main pages Jekyll-Bootstrap ships with.
  # Some JB helpers refer to these paths; change them here if needed.
  #
  archive_path: nil
  categories_path : nil
  tags_path : nil
  atom_path : nil
  rss_path : nil

  # Settings for comments helper
  # Set 'provider' to the comment provider you want to use.
  # Set 'provider' to false to turn commenting off globally.
  #
  comments :
    provider : false

  # Settings for analytics helper
  # Set 'provider' to the analytics provider you want to use.
  # Set 'provider' to false to turn analytics off globally.
  #
  analytics :
    provider : false

  # Settings for sharing helper.
  # Sharing is for things like tweet, plusone, like, reddit buttons etc.
  # Set 'provider' to the sharing provider you want to use.
  # Set 'provider' to false to turn sharing off globally.
  #
  sharing :
    provider : false

  # Settings for all other include helpers can be defined by creating
  # a hash with key named for the given helper. ex:
  #
  #   pages_list :
  #     provider : "custom"
  #
  # Setting any helper's provider to 'custom' will bypass the helper code
  # and include your custom code. Your custom file must be defined at:
  #   ./_includes/custom/[HELPER]
  # where [HELPER] is the name of the helper you are overriding.
