# Django Templates for use django-filer with [django-admin-bootstrap](https://github.com/douglasmiranda/django-admin-bootstrap)

django-filer is a "File and Image Management Application for django".

## How to use these templates

Well let's considering that you already have created a django project.

So you want a media management in your django admin, and want the awesome django admin interface  fully customized with Twitter Bootstrap.

**You will have to:**

* install the [django-filer](https://github.com/stefanfoulis/django-filer)
* install the [django-admin-bootstrap](https://github.com/douglasmiranda/django-admin-bootstrap)
* install the customized templates for django-filer (see below)

**Installing the templates**

you can obtain just [downloading it](https://github.com/douglasmiranda/django-filer-bootstrap-admin-templates/archive/master.zip)

or cloning the repo

```
>>> git clone https://github.com/douglasmiranda/django-filer-bootstrap-admin-templates
```

Then:

Copy all the contents from __templates/*__ and paste in your _templates/_ directory.

Copy all the contents from __static/*__ and paste in your _static/_ directory.

Well.. this is it.

If you have an issue, [create an issue](https://github.com/douglasmiranda/django-filer-bootstrap-admin-templates/issues/new), if you want to fix the issue, fork this repo and send me a pull request.

## NOTES

* Templates from django-filer version __0.9__
* Latest version working with django==1.5
* You can get the version compatible with django==1.4.* [here](https://github.com/douglasmiranda/django-filer-bootstrap-admin-templates/tree/v0.1) and you will have to use the [django-admin-bootstrap](https://github.com/douglasmiranda/django-admin-bootstrap) in version 0.1.5 `pip install bootstrap-admin==0.1.5`