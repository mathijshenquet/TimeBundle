Provide a time helper to Symfony2 projects.

## INSTALLATION

Enable the helper in your config.yml:

    time.helper: ~      # Enable the helper for use in templates

## USAGE

    // Use the helper with Php
    echo $view->time->ago($dateTime); // returns something like "3 minutes ago"
    // Use the helper with twig
    {{ _view.time.ago(DateTimeObject) }}

