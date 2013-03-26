Sublime Build System for running Drupal Code Sniffer on your Drupal files.

1. Follow the directions for the [Drupal Code Sniffer][1] project.
2. Place the DrupalCodingStandard.sublime-build file into your Packages/User directory.
   (On OS X this is ~/Library/Application Support/Sublime Text 2/Packages/User)
3. Open up Sublime Text 2 and select Tools > Build System > DrupalCodingStandard
4. Open any Drupal file and hit Cmd+B
5. You can make reporting more compress with "--report=full". In this case sniffer will show only line number(without full path to file)

[1]: http://drupal.org/project/drupalcs
