gerrit-repo
===========

Generate repo config for all gerrit repositories

Given a gerrit base url, and download json of all projects generates repo compatible manifest.

$ ./gerrit-repo --help
usage: gerrit-repo [-h] [-u BASEURL] [-j JSON] [-o OUTPUT] [-n NAME]

optional arguments:
  -h, --help            show this help message and exit
  -u BASEURL, --baseurl BASEURL
                        Gerrit instance url
  -j JSON, --json JSON  Downloaded json projects file
  -o OUTPUT, --output OUTPUT
                        Repo xml config output
  -n NAME, --name NAME  Default name
