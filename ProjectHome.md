## Note: This project has moved to [elo80ka/django-dynamic-formset](https://github.com/elo80ka/django-dynamic-formset) on Github. ##

Based on [this snippet](http://www.djangosnippets.org/snippets/1389/) on http://djangosnippets.org, this jQuery plugin helps you create more usable formsets by allowing clients add and remove forms on the client-side.

The code for the snippet was extracted from a project I worked on. After using it on a few other projects, I thought it'd be a good idea to make it even easier to use with my current javascript library.

## Installation instructions ##

There are two ways to install this application for use by your
projects; the first is to do a Subversion checkout:
```
svn co http://django-dynamic-formset.googlecode.com/svn/trunk/ django-dynamic-formset
```
The second method is to download a packaged release. The latest
release is 1.2. You can download the source and documentation only,
or include the demo project:
```
wget http://django-dynamic-formset.googlecode.com/files/jquery.formset-1.2.zip
unzip jquery.formset-1.2.zip -d jquery.formset-1.2
cd jquery.formset-1.2
```
The plugin files are in the `src/` directory. If you downloaded
the archive with the demo project, you'll need to set it up first.

### Setting up the demo project ###

The demo project is a Django project, showing different ways to
use the plugin. To run the project, you'll need [Python](http://python.org/) and [Django](http://www.djangoproject.com/).
For instructions on installing them, see their respective sites.

You'll also need [PySQLite](http://oss.itsystementwicklung.de/trac/pysqlite) - if you've got Python 2.5 and above, this is already included in the standard library.

Once you've set up Django, run the following commands to set up the
database and start the development server:
```
cd demo
python ./manage.py syncdb
python ./manage.py runserver
```
You can now browse to `http://localhost:8000/` and view the examples.