# docker-patterns
This is a repo of docker patterns, i.e. things that I do often when creating new Dockerfiles that may or may not be the best approach but it is what I found to work.

If you see a pattern that can be done in a better way send me a pull request.

 * debian_clean_dev - A pattern to install packages temporarily for compiling and then remove them via dpkg --get/set-selections.
 * debian_apt_env   - Non-interactive + LC_ALL/LANG environment variables for apt-get operations.
