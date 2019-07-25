# Unleash Django
Atom enhanced support for Django

## Description
***Unleash Django*** is an **Atom** editor package made for web developers with a concern of productivity.
Its goal is to give an enhanced support of the **Django framework** to this text editor.
It is continuously updated in order to be consistent with the latest stable Django release.

The objective is to regroup some best practices from:
- [Two Scoops of Django](https://www.twoscoopspress.com)
- [Django official documentation](https://docs.djangoproject.com/)

## Installation
There are three ways to install *Unleash Django*:
* Open Atom, go to *Settings -> Install -> Package Search*, and search **unleash-django**
* Using Atom Package Manager in your terminal ```apm install unleash-django```
* In your terminal, go to ```~/.atom/packages``` and execute ```git clone https://github.com/hectocore/unleash-django.git```

## Usage
Just open a file of your Django project and you're ready to go!

***Unleash Django*** gives you a lot of **snippets** to use in all parts of your project. It will also adjust the **appearance** of your code, in order to fit with Django's functionalities. Last but not least, it works with **HTML templates**!

## Snippets
Here is a list of all available snippets:

Note that you can abbreviate the prefix, for example if you type ***mdt***, Atom will understand that you mean ***model-date-time*** and will automaticaly create a **Model DateTimeField**.

### Django Admin Snippets
![Unleash Django: example of admin-model use](unleash-django_-_example_admin-model.gif)


| Prefix                            | Content                                  |
|-----------------------------------|------------------------------------------|
| admin-model                       | Admin ModelAdmin                         |
| admin-model-manual                | Admin ModelAdmin (manual)                |
| admin-site-register               | Admin Site Register                      |
| admin-stacked                     | Admin StackedInline                      |
| admin-tabular                     | Admin TabularInline                      |

### Django Form Snippets

| Prefix                            | Content                                  |
|-----------------------------------|------------------------------------------|
| form                              | Form                                     |
| form-model                        | ModelForm                                |

### Django Model Snippets

| Prefix                            | Content                                  |
|-----------------------------------|------------------------------------------|
| model                             | Model                                    |
| model-auto                        | Model AutoField                          |
| model-bigint                      | Model BigInteger                         |
| model-bin                         | Model BinaryField                        |
| model-bool                        | Model BooleanField                       |
| model-char                        | Model CharField                          |
| model-date                        | Model DateField                          |
| model-date-time                   | Model DateTimeField                      |
| model-dec                         | Model DecimalField                       |
| model-duration                    | Model DurationField                      |
| model-email                       | Model EmailField                         |
| model-file                        | Model FileField                          |
| model-path                        | Model FilePathField                      |
| model-float                       | Model FloatField                         |
| model-fkey                        | Model ForeignKey                         |
| model-img                         | Model ImageField                         |
| model-int                         | Model IntegerField                       |
| model-gip                         | Model GenericIPAddressField              |
| model-mtm                         | Model ManyToManyField                    |
| model-nbool                       | Model NullBooleanField                   |
| model-1t1                         | Model OneToOneField                      |
| model-pint                        | Model PositiveIntegerField               |
| model-psint                       | Model PositiveSmallIntegerField          |
| model-slug                        | Model SlugField                          |
| model-sint                        | Model SmallIntegerField                  |
| model-text                        | Model TextField                          |
| model-time                        | Model TimeField                          |
| model-url                         | Model URLField                           |
| model-uuid                        | Model UUIDField                          |

### Django URL Snippets

| Prefix                            | Content                                  |
|-----------------------------------|------------------------------------------|
| url                               | URL                                      |
| url-main                          | URL (main)                               |
| url-patterns                      | URL Patterns                             |

### Django View Snippets

| Prefix                            | Content                                  |
|-----------------------------------|------------------------------------------|
| view                              | View                                     |

### Django REST Framework Snippets

| Prefix                            | Content                                  |
|-----------------------------------|------------------------------------------|
| rest-serializer                   | Django REST Serializer                   |
| rest-view-list-create             | Django REST ListCreateAPIView            |
| rest-view-retrieve-update-destroy | Django REST RetrieveUpdateDestroyAPIView |
