# YUL (pywb) Wayback

## Usage

### Production

* `docker run -it --rm --network host -v "/mnt/omega/web-archives/:/webarchive" -v "/mnt/omega/web-archives/uwsgi.ini:/uwsgi/uwsgi.ini" webrecorder/pywb:2.8.3`
* https://wayback.library.yorku.ca/

### Local (dev)

* `git clone git@github.com:yorkulibraries/web-archives.git`
* `docker run -it --rm -p 80:8080 -v "/path/to/web-archives:/webarchive" webrecorder/pywb:2.7.4`
* http://localhost/
