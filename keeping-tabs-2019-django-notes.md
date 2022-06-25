# Django Code Notes

<!--
## Django Database

DB Relationships

Queryset API Reference
Queryset methods
https://docs.djangoproject.com/en/4.0/ref/models/querysets/
https://docs.djangoproject.com/en/4.0/ref/models/querysets/#queryset-api-1
Queryset field lookups
https://docs.djangoproject.com/en/4.0/ref/models/querysets/#field-lookups-1
https://docs.djangoproject.com/en/4.0/ref/models/expressions/
https://docs.djangoproject.com/en/4.0/ref/models/lookups/

Double underscores to span a relationship
https://docs.djangoproject.com/en/4.0/topics/db/queries/#lookups-that-span-relationships

Model Fields
https://docs.djangoproject.com/en/4.0/ref/models/fields/


pk
https://docs.djangoproject.com/en/4.0/ref/models/fields/#primary-key
https://en.wikipedia.org/wiki/Primary_key


select_related (foreign key, related objects)
https://docs.djangoproject.com/en/4.0/ref/models/querysets/#django.db.models.query.QuerySet.select_related

prefetch_related (many-to-many)
https://docs.djangoproject.com/en/4.0/ref/models/querysets/#django.db.models.query.QuerySet.prefetch_related

select related and pre-fetch related
https://docs.djangoproject.com/en/4.0/ref/models/querysets/#select-related
https://docs.djangoproject.com/en/4.0/ref/models/querysets/#prefetch-objects
https://docs.djangoproject.com/en/4.0/ref/models/querysets/#prefetch-related-objects
-->


## Help

Enter the Python help utility

```python
>>> help()
```

Obtain help for a specific object

```python
>>> help(object)
```

Exit the Python help utility

```python
>>> q
```

## Check Objects

Without arguments, return the list of names in the current local scope. With an argument, attempt to return a list of valid attributes for that object.

```dir()```

Return True if the object argument appears callable, False if not. 

```callable()```

With one argument, return the type of an object. 

```type()```



## Helpful for Debugging

Commonly used ```Model``` attributes

```python
pk (Model attribute), 1149 
save() (Model method), 1149 
delete() (Model method), 1152 
```

<!--
6.3. The dir() Function
https://docs.python.org/3/tutorial/modules.html#the-dir-function
https://docs.python.org/3/library/functions.html#dir

https://docs.python.org/3/library/functions.html#type

https://docs.djangoproject.com/en/4.0/topics/db/queries/

https://docs.python.org/3/reference/datamodel.html
https://docs.python.org/3/library/stdtypes.html#special-attributes
https://docs.python.org/3/library/stdtypes.html#object.__dict__

https://docs.djangoproject.com/en/4.0/intro/tutorial02/
-->



## Classes and Functions

Define a function or class

```python
def function():
class Class:
```

Function statement

```python
def function():
    """Description"""
    action

function()
```

Class statement

```python
class Class:
    """Description"""
    def __init__(self, attribute):
        self.attribute = attribute
 
    def method(self):
        action
```


## Models

Classes in ```django.db.models```

```python
ForeignKey (class in django.db.models), 1117 
ManyToManyField (class in django.db.models), 1121 
```

```
from django.db import models

# Many has ForeignKey
class Car(models.Model):
    manufacturer = models.ForeignKey(
        'Manufacturer',
        on_delete=models.CASCADE,
    )
    # ...

# One
class Manufacturer(models.Model):
    # ...
    pass
```

```
from django.db import models

# Many
class Publication(models.Model):
    title = models.CharField(max_length=30)

    class Meta:
        ordering = ['title']

    def __str__(self):
        return self.title

# Many
class Article(models.Model):
    headline = models.CharField(max_length=100)
    publications = models.ManyToManyField(Publication)

    class Meta:
        ordering = ['headline']

    def __str__(self):
        return self.headline
```
 
<!--
ForeignKey (Many to One)
https://docs.djangoproject.com/en/4.0/ref/models/fields/#django.db.models.ForeignKey
Many to One
https://docs.djangoproject.com/en/4.0/topics/db/examples/many_to_one/

ManyToManyField
https://docs.djangoproject.com/en/4.0/topics/db/examples/many_to_many/
https://www.revsys.com/tidbits/tips-using-djangos-manytomanyfield/

ForeignKey and ManyToManyField database explainer
https://www.mattlayman.com/understand-django/store-data-with-models/
-->

```python
OneToOneField (class in django.db.models), 1124 
```

<!--
OnetoOneField
https://docs.djangoproject.com/en/4.0/topics/db/examples/one_to_one/
-->

Commonly used ```ForeignKey``` attributes

```python
related_name (ForeignKey attribute), 1120 
on_delete (ForeignKey attribute), 1118 
```

Commonly used ```ManyToManyField``` attributes

```python
related_name (ManyToManyField attribute), 1122 
through (ManyToManyField attribute), 1122 
```

<!--
Related Manager (Used in a one-to-many or many-to-many related context, set, add, etc.)
The “other side” of a ForeignKey relation.
Both sides of a ManyToManyField relation.
https://docs.djangoproject.com/en/4.0/ref/models/relations/#django.db.models.fields.related.RelatedManager.add

related name versus set
https://www.revsys.com/tidbits/tips-using-djangos-manytomanyfield/
-->


More ```ForeignKey``` attributes

```python
db_constraint (ForeignKey attribute), 1121 
limit_choices_to (ForeignKey attribute), 1119 
related_query_name (ForeignKey attribute), 1120 
swappable (ForeignKey attribute), 1121 
to_field (ForeignKey attribute), 1121 
```

More ```ManyToManyField``` attributes

```python
db_constraint (ManyToManyField attribute), 1123 
db_table (ManyToManyField attribute), 1123 
limit_choices_to (ManyToManyField attribute), 1122 
related_query_name (ManyToManyField attribute), 1122 
symmetrical (ManyToManyField attribute), 1122 
swappable (ManyToManyField attribute), 1123 
through_fields (ManyToManyField attribute), 1122 
```

```OneToOneField``` attribute

```python
parent_link (OneToOneField attribute), 1125 
```

```GenericForeignKey``` attribute

```python
for_concrete_model (GenericForeignKey attribute), 765 
```

<!--
from_db() (django.db.models.Model class method), 1144 

CASCADE (in module django.db.models), 1119 

as_sql() (in module django.db.models), 1208 
as_vendorname() (in module django.db.models), 1208 
DO_NOTHING (in module django.db.models), 1119 
from_queryset() (in module django.db.models), 138 
get_lookup() (in module django.db.models), 1208 
get_transform() (in module django.db.models), 1209 
output_field (in module django.db.models), 1209 
prefetch_related_objects() (in module django.db.models), 1206 
PROTECT (in module django.db.models), 1119 
SET() (in module django.db.models), 1119 
SET_DEFAULT (in module django.db.models), 1119 
SET_NULL (in module django.db.models), 1119 
-->


## Model Methods

Commonly used ```Model``` attributes

```python
pk (Model attribute), 1149 
save() (Model method), 1149 
delete() (Model method), 1152 
```


```python
clean() (Model method), 1147 
get_absolute_url() (Model method), 1153 
```

```python
_base_manager (Model attribute), 136 
_default_manager (Model attribute), 136 
objects (Model attribute), 1136 

 __eq__() (Model method), 1153 
__hash__() (Model method), 1153 
__str__() (Model method), 1152 
clean_fields() (Model method), 1147 
full_clean() (Model method), 1146 
get_deferred_fields() (Model method), 1146 
get_FOO_display() (Model method), 1154 
get_next_by_FOO() (Model method), 1155 
get_previous_by_FOO() (Model method), 1155 
refresh_from_db() (Model method), 1145 
validate_unique() (Model method), 1148 
```

## Model Options

<!--
https://docs.djangoproject.com/en/2.1/ref/models/options/

Options (class in django.db.models.options), 1129 
-->

Meta- Most commonly used

```python
get_latest_by (Options attribute), 1138 
ordering (Options attribute), 1140 
unique_together (Options attribute), 1142 
verbose_name (Options attribute), 1143 
verbose_name_plural (Options attribute), 1143 
order_with_respect_to (Options attribute), 1139 
```

```python
abstract (Options attribute), 1136 
default_manager_name (Options attribute), 1137 
default_permissions (Options attribute), 1141 
default_related_name (Options attribute), 1137 
app_label (Options attribute), 1136 
base_manager_name (Options attribute), 1136 
db_table (Options attribute), 1136 
db_tablespace (Options attribute), 1137 
index_together (Options attribute), 1142 
indexes (Options attribute), 1141 
label (Options attribute), 1143 
label_lower (Options attribute), 1143 
managed (Options attribute), 1138 
permissions (Options attribute), 1140 
proxy (Options attribute), 1141 
required_db_features (Options attribute), 1141 
required_db_vendor (Options attribute), 1141 
select_on_save (Options attribute), 1141 

get_field() (Options method), 1129 
get_fields() (Options method), 1130 
```

## Model Field Attributes and Methods

<!--
Model field attributes
-->

Commonly used

```python
auto_created (Field attribute), 1127 
blank (Field attribute), 1102 
choices (Field attribute), 1102 
default (Field attribute), 1104 
editable (Field attribute), 1105 
help_text (Field attribute), 1049, 1105 
label (Field attribute), 1047 
null (Field attribute), 1102 
related_model (Field attribute), 1128 
required (Field attribute), 1046 
unique (Field attribute), 1106 
verbose_name (Field attribute), 1106 
widget (Field attribute), 1049 
```

```python
many_to_many (Field attribute), 1128 
many_to_one (Field attribute), 1128 
one_to_many (Field attribute), 1128 
one_to_one (Field attribute), 1128 
primary_key (Field attribute), 1105 
```

```python
concrete (Field attribute), 1127 
db_column (Field attribute), 1104 
db_index (Field attribute), 1104 
db_tablespace (Field attribute), 1104 
description (Field attribute), 1125 
disabled (Field attribute), 1051 
error_messages (Field attribute), 1050, 1105 
geom_type (Field attribute), 809 
hidden (Field attribute), 1127 
initial (Field attribute), 1048 
is_relation (Field attribute), 1127 
label_suffix (Field attribute), 1047 
localize (Field attribute), 1050 
model (Field attribute), 1127 
name (Field attribute), 855 
precision (Field attribute), 855 
type (Field attribute), 855 
type_name (Field attribute), 855 
unique_for_date (Field attribute), 1106 
unique_for_month (Field attribute), 1106 
unique_for_year (Field attribute), 1106 
validators (Field attribute), 1050, 1107 
value (Field attribute), 855 
width (Field attribute), 855 
```

```python
as_datetime() (Field method), 856 
as_double() (Field method), 856 
as_int() (Field method), 856 
as_string() (Field method), 856 
clean() (Field method), 1046 
db_type() (Field method), 1125 
deconstruct() (Field method), 1127 
formfield() (Field method), 1127 
from_db_value() (Field method), 1126 
get_bound_field() (Field method), 1043 
get_db_prep_save() (Field method), 1126 
get_db_prep_value() (Field method), 1126 
get_internal_type() (Field method), 1125 
get_prep_value() (Field method), 1126 
has_changed() (Field method), 1051 
pre_save() (Field method), 1126 
rel_db_type() (Field method), 1125 
to_python() (Field method), 1126 
value_from_object() (Field method), 1126 
value_to_string() (Field method), 1126 
```


<!--
<Object>.objects.all()
-->

## QuerySet

```python
QuerySet (class in django.db.models.query), 1157 
```

### QuerySet Attributes

<!--
https://docs.djangoproject.com/en/2.1/ref/request-response/#django.http.QueryDict
-->

```python
db (QuerySet attribute), 1157 
ordered (QuerySet attribute), 1157 
```


### QuerySet Methods- Commonly Used

Does not return a queryset; takes field lookup types as keyword arguments (same as SQL WHERE clause)

```python
get() (in module django.db.models.query.QuerySet), 1182 
```

Return a queryset; take field lookup types as keyword arguments (same as SQL WHERE clause)

```python
filter() (in module django.db.models.query.QuerySet), 1158 
exclude() (in module django.db.models.query.QuerySet), 1158 
```

Returns a queryset

```python
all() (in module django.db.models.query.QuerySet), 1167 
```


## QuerySet Methods That Do Not Return QuerySets

Exists, Get, Create, Update, Delete

```python
exists() (in module django.db.models.query.QuerySet), 1190 
get() (in module django.db.models.query.QuerySet), 1182 
create() (in module django.db.models.query.QuerySet), 1182 
get_or_create() (in module django.db.models.query.QuerySet), 1183 
update() (in module django.db.models.query.QuerySet), 1190 
update_or_create() (in module django.db.models.query.QuerySet), 1185 
bulk_create() (in module django.db.models.query.QuerySet), 1185 
delete() (in module django.db.models.query.QuerySet), 1191 
```

Order- Latest, Earliest, First, Last

```python
earliest() (in module django.db.models.query.QuerySet), 1189 
first() (in module django.db.models.query.QuerySet), 1189 
last() (in module django.db.models.query.QuerySet), 1189 
latest() (in module django.db.models.query.QuerySet), 1188 
```

Utility

```python
count() (in module django.db.models.query.QuerySet), 1186 
in_bulk() (in module django.db.models.query.QuerySet), 1187 
as_manager() (in module django.db.models.query.QuerySet), 1192 
```

Iterator and Aggregate

```python
iterator() (in module django.db.models.query.QuerySet), 1187 
aggregate() (in module django.db.models.query.QuerySet), 1189 
```


## QuerySet Methods That Return QuerySets

<!--
https://docs.djangoproject.com/en/2.1/ref/models/querysets/#none
-->

None

```python
none() (in module django.db.models.query.QuerySet), 1167
```

Common

```python
all() (in module django.db.models.query.QuerySet), 1167 
filter() (in module django.db.models.query.QuerySet), 1158 
exclude() (in module django.db.models.query.QuerySet), 1158 
```

Dates

```python
dates() (in module django.db.models.query.QuerySet), 1166 
datetimes() (in module django.db.models.query.QuerySet), 1166 
```

Order

```python
order_by() (in module django.db.models.query.QuerySet), 1159 
reverse() (in module django.db.models.query.QuerySet), 1161 
```

Data Structures

```python
values() (in module django.db.models.query.QuerySet), 1162 
values_list() (in module django.db.models.query.QuerySet), 1165 
raw() (in module django.db.models.query.QuerySet), 1181 
```

Optimization

```python
defer() (in module django.db.models.query.QuerySet), 1177 
only() (in module django.db.models.query.QuerySet), 1179 
```

Utility

```python
using() (in module django.db.models.query.QuerySet), 1179 
```

Last Resort

```python
extra() (in module django.db.models.query.QuerySet), 1174 
```

Query-Related Tools

```python
annotate() (in module django.db.models.query.QuerySet), 1158 
distinct() (in module django.db.models.query.QuerySet), 1161 
prefetch_related() (in module django.db.models.query.QuerySet), 1170 
select_for_update() (in module django.db.models.query.QuerySet), 1180 
select_related() (in module django.db.models.query.QuerySet), 1168 
```

Stats

```python
union() (in module django.db.models.query.QuerySet), 1167 
intersection() (in module django.db.models.query.QuerySet), 1168 
difference() (in module django.db.models.query.QuerySet), 1168 
```

<!--
New
explain() (in module django.db.models.query.QuerySet), 1192 
-->


## Django Field Look-Up Types

Is Null

```python
isnull field lookup type, 1201 
```

Greater Than/Equals, Less Than/Equals

```python
gt field lookup type, 1195 
gte field lookup type, 1196 
lt field lookup type, 1196 
lte field lookup type, 1196 
```

Time

```python
time field lookup type, 1200 
year field lookup type, 1198 
quarter field lookup type, 1200
month field lookup type, 1198 
week field lookup type, 1199
date field lookup type, 1198 (Field Lookup Type and Template Filter)
day field lookup type, 1199 
week_day field lookup type, 1199 
hour field lookup type, 1200 
minute field lookup type, 1201 
second field lookup type, 1201 
```

Exact

```python
exact field lookup type, 815, 1193 
iexact field lookup type, 1193 (Case-Insensitive)
```

Search, Contains

```python
search field lookup type, 922 
contains field lookup type, 1194 
icontains field lookup type, 1194 (Case-Insensitive) 
```

Starts With/Ends With

```python
startswith field lookup type, 1196 
endswith field lookup type, 1197 
istartswith field lookup type, 1196 (Case-Insensitive)  
iendswith field lookup type, 1197 (Case-Insensitive)  
```

In, Range

```python
in field lookup type, 1195 
range field lookup type, 1197 
```

Regex

```python
regex field lookup type, 1202 
iregex field lookup type, 1202 (Case-Insensitive)
```


## Testing

### SimpleTestCase

allow_database_queries (SimpleTestCase attribute), 341 
client (SimpleTestCase attribute), 344 
client_class (SimpleTestCase attribute), 345 

assert
assertContains() (SimpleTestCase method), 351 
assertFieldOutput() (SimpleTestCase method), 350 
assertFormError() (SimpleTestCase method), 351 
assertFormsetError() (SimpleTestCase method), 351 
assertHTMLEqual() (SimpleTestCase method), 352 
assertHTMLNotEqual() (SimpleTestCase method), 353 
assertInHTML() (SimpleTestCase method), 353 
assertJSONEqual() (SimpleTestCase method), 353 
assertJSONNotEqual() (SimpleTestCase method), 353 
assertNotContains() (SimpleTestCase method), 351 
assertRaisesMessage() (SimpleTestCase method), 350 
assertRedirects() (SimpleTestCase method), 352 
assertTemplateNotUsed() (SimpleTestCase method), 352 
assertTemplateUsed() (SimpleTestCase method), 351 
assertWarnsMessage() (SimpleTestCase method), 350 
assertXMLEqual() (SimpleTestCase method), 353 
assertXMLNotEqual() (SimpleTestCase method), 353 

modify_settings() (SimpleTestCase method), 347 
settings() (SimpleTestCase method), 347 

### TransactionTestCase

available_apps (TransactionTestCase attribute), 360 
fixtures (TransactionTestCase attribute), 345 
multi_db (TransactionTestCase attribute), 346 

assert
assertNumQueries() (TransactionTestCase method), 354 
assertQuerysetEqual() (TransactionTestCase method), 353 
```

<!--
NON_FIELD_ERRORS (in module django.core.exceptions), 1017 

### Checks

CheckMessage (class in django.core.checks), 635 
Critical (class in django.core.checks), 636 
Debug (class in django.core.checks), 636 
Error (class in django.core.checks), 636 
Info (class in django.core.checks), 636 
register() (in module django.core.checks), 535 
Warning (class in django.core.checks), 636 

## SafeExceptionReporter

SafeExceptionReporterFilter (class in django.views.debug), 596 
get_post_parameters() (SafeExceptionReporterFilter method), 596 
get_traceback_frame_variables() (SafeExceptionReporterFilter method), 596 
is_active() (SafeExceptionReporterFilter method), 596 

### Runner

DiscoverRunner (class in django.test.runner), 363 
add_arguments() (django.test.runner.DiscoverRunner class method), 364 

### Test

setUpTestData() (django.test.TestCase class method), 342 

Client (class in django.test), 333 
LiveServerTestCase (class in django.test), 343 
RequestFactory (class in django.test), 357 
Response (class in django.test), 337 

TestCase (class in django.test), 342 
SimpleTestCase (class in django.test), 341 
TransactionTestCase (class in django.test), 342 

reset_sequences (TransactionTestCase attribute), 361 

modify_settings() (in module django.test), 348 
override_settings() (in module django.test), 348 
skipIfDBFeature() (in module django.test), 356 
skipUnlessDBFeature() (in module django.test), 356 

setup_databases() (in module django.test.utils), 365 
setup_test_environment() (in module django.test.utils), 365 
teardown_databases() (in module django.test.utils), 365 
teardown_test_environment() (in module django.test.utils), 365 

django.test.signals.setting_changed (built-in variable), 1321 
django.test.signals.template_rendered (built-in variable), 1321 
django.test.utils.isolate_apps() (built-in function), 1781 

### Validators (Model and Form Fields

DecimalValidator (class in django.core.validators), 1417 
EmailValidator (class in django.core.validators), 1415 
FileExtensionValidator (class in django.core.validators), 1418 
int_list_validator() (in module django.core.validators), 1417 
MaxLengthValidator (class in django.core.validators), 1417 
MaxValueValidator (class in django.core.validators), 1417 
MinLengthValidator (class in django.core.validators), 1417 
MinValueValidator (class in django.core.validators), 1417 
ProhibitNullCharactersValidator (class in django.core.validators), 1418 
RegexValidator (class in django.core.validators), 1415 
URLValidator (class in django.core.validators), 1416 

code (EmailValidator attribute), 1415 
code (ProhibitNullCharactersValidator attribute), 1418 
code (RegexValidator attribute), 1415 
flags (RegexValidator attribute), 1415 
inverse_match (RegexValidator attribute), 1415 
message (EmailValidator attribute), 1415 
message (ProhibitNullCharactersValidator attribute), 1418 
message (RegexValidator attribute), 1415 
regex (RegexValidator attribute), 1415 
schemes (URLValidator attribute), 1416 
whitelist (EmailValidator attribute), 1415 

validate_comma_separated_integer_list (in module django.core.validators), 1417 
validate_email (in module django.core.validators), 1416 
validate_image_file_extension (in module django.core.validators), 1418 
validate_ipv46_address (in module django.core.validators), 1416 
validate_ipv4_address (in module django.core.validators), 1416 
validate_ipv6_address (in module django.core.validators), 1416 
validate_slug (in module django.core.validators), 1416 
validate_unicode_slug (in module django.core.validators), 1416 

### Log

AdminEmailHandler (class in django.utils.log), 501 
CallbackFilter (class in django.utils.log), 502 
RequireDebugFalse (class in django.utils.log), 503 
RequireDebugTrue (class in django.utils.log), 503 
-->

## Testing

### DiscoverRunner

```python
test_loader (DiscoverRunner attribute), 364 
test_runner (DiscoverRunner attribute), 363 
test_suite (DiscoverRunner attribute), 363 

build_suite() (DiscoverRunner method), 364 
get_test_runner_kwargs() (DiscoverRunner method), 364
run_checks() (DiscoverRunner method), 364 
run_suite() (DiscoverRunner method), 364 
run_tests() (DiscoverRunner method), 364 
suite_result() (DiscoverRunner method), 365 

setup_databases() (DiscoverRunner method), 364 
setup_test_environment() (DiscoverRunner method), 364 
teardown_databases() (DiscoverRunner method), 365 
teardown_test_environment() (DiscoverRunner method), 365 


## Template Tags

<!--
templatetag, 1348 
-->

## Template Tags- Control Flow

```python
cycle template tag, 1333 
resetcycle template tag, 1347 
firstof template tag, 1336 
for template tag, 1336 

if template tag, 1337 (operators)
ifchanged template tag, 1341 
```

<!--
Deprecated?
for ... empty
-->

### Template Tags- Other Common

Static

```python
static template tag, 1369 
```

Templates

```python
block template tag, 1332 
extends template tag, 1335 
include template tag, 1342 
```

URL

```python
url template tag, 1348 
```

Filter (See Below)

```python
filter template tag, 1335 
```

CSRF

```python
csrf_token template tag, 1333 
```

Comment

```python
comment template tag, 1332 
```

Language

```python
trans template tag, 457 
```

Date, Time, Localization

```python
get_current_timezone template tag, 487 
localize, template tag, 481 (Template Filter and Template Tag)  
localtime, template tag, 486 (Template Filter and Template Tag) 
now template tag, 1344 
timezone template tag, 486 (Template Filter and Template Tag)
```

## Template Tags- Less Common

Templates

```python
load template tag, 1343 
```

<!--
Deprecated?

Templates
* templatetag

Static
* staticfiles-static
-->

Static and Media Prefixes

```python
get_media_prefix template tag, 1370 
get_static_prefix template tag, 1369 
```

Flatpages

```python
get_flatpages template tag, 772 
```

Language

```python
get_available_languages template tag, 461 
get_current_language template tag, 461 
get_current_language_bidi template tag, 461 
get_language_info template tag, 462 
get_language_info_list template tag, 462 
language template tag, 461 
blocktrans template tag, 458 
```

Autoescape

```python
autoescape, 1332
```

Cache

```python 
cache template tag, 423 
with template tag, 1350 
```

Lorem

```python
lorem template tag, 1343 
```

Regroup

```python
regroup template tag, 1344 
```

Bar Charts and Such

```python
widthratio template tag, 1350 
```

Escape

```python
verbatim template tag, 1349 
```

Spaceless

```python
spaceless template tag, 1347 
```

Debug

```python
debug template tag, 1335 
```

## Template Filters- Data Structures

List

```python
make_list template filter, 1360 
unordered_list template filter, 1366
```

First and Last of List

```python
first template filter, 1356 
last template filter, 1358
```

Dictsort

```python
dictsort template filter, 1354 
dictsortreversed template filter, 1355 
```

## Template Filters- General

Default

```python
default template filter, 1353 
default_if_none template filter, 1354 
```

Length

```python
length template filter, 1359 
length_is template filter, 1359 
```

Slug

```python
slugify template filter, 1362 
```

Urlize

```python
urlize template filter, 1366 
urlizetrunc template filter, 1367 
```

Numerical Operations

```python
add template filter, 1351 
divisibleby template filter, 1355 
floatformat template filter, 1356 
random template filter, 1361 
slice template filter, 1362 
```

Date, Time, and Localization

```python
date template filter, 1352 (Field Lookup Type and Template Filter)
localize template filter, 481 (Field Lookup Type and Template Filter)
localtime template filter, 487 (Field Lookup Type and Template Filter)
naturalday template filter, 890 
naturaltime template filter, 890 
time template filter, 1363 
timesince template filter, 1364 
timeuntil template filter, 1364 
timezone template filter, 487 (Template Filter and Template Tag)
unlocalize template filter, 482 
```

Title/Text

```python
capfirst template filter, 1351 
title template filter, 1364 
upper template filter, 1366 
lower template filter, 1360 
pluralize template filter, 1361 
wordwrap template filter, 1368 
```

Centering and Justification

```python
center template filter, 1351 
ljust template filter, 1360 
rjust template filter, 1361 
```

Truncate

```python
truncatechars template filter, 1365 
truncatechars_html template filter, 1365 
truncatewords template filter, 1365 
truncatewords_html template filter, 1365 
```

Cut/Strip

```python
cut template filter, 1351 
striptags template filter, 1363 
```

<!--
removetags (deprecated, use Bleach)
-->

Line Breaks and Line Numbers

```python
linebreaks template filter, 1359 
linebreaksbr template filter, 1359 
linenumbers template filter, 1359 
```

Escape and Safe

```python
addslashes template filter, 1351 
escape template filter, 1355 
escapejs template filter, 1356 
force_escape template filter, 1357 
safe template filter, 1362 
safeseq template filter, 1362 
```

Language

```python
language_bidi template filter, 462 
language_name template filter, 462 
language_name_local template filter, 462 
language_name_translated template filter, 462 
```

File Size

```python
filesizeformat template filter, 1356 
```

Debug

```python
pprint template filter, 1361 
```

More

```python
apnumber template filter, 889 
get_digit template filter, 1357 
intcomma template filter, 889 
intword template filter, 889 
iriencode template filter, 1358 
join template filter, 1358 
ordinal template filter, 891 
phone2numeric template filter, 1360 
stringformat template filter, 1363 
urlencode template filter, 1366 
utc template filter, 487 
wordcount template filter, 1367 
yesno template filter, 1368 
```
<!--
New

json_script template filter, 1358 
-->


## URLs and Shortcuts

```python
render() (in module django.shortcuts), 207 
redirect() (in module django.shortcuts), 209 

get_list_or_404() (in module django.shortcuts), 211 
get_object_or_404() (in module django.shortcuts), 210 

handler400 (in module django.conf.urls), 1399 
handler403 (in module django.conf.urls), 1399 
handler404 (in module django.conf.urls), 1399 
handler500 (in module django.conf.urls), 1399 

No longer used
render_to_response() (in module django.shortcuts), 208 
```

```python
reverse() (in module django.urls), 1394 
reverse_lazy() (in module django.urls), 1395 

url() (in module django.conf.urls), 1399 
include() (in module django.urls), 1398 
path() (in module django.urls), 1397 
re_path() (in module django.urls), 1397 
static.static() (in module django.conf.urls), 1398 

get_script_prefix() (in module django.urls), 1396 
register_converter() (in module django.urls), 1398 
ResolverMatch (class in django.urls), 1395 
resolve() (in module django.urls), 1395 

i18n_patterns() (in module django.conf.urls.i18n), 468 
```

<!--
Templates

Origin (class in django.template.base), 1385 

SimpleTemplateResponse (class in django.template.response), 1385 
TemplateResponse (class in django.template.response), 1387 

Loader (class in django.template.loaders.base), 1384 
render_to_string() (in module django.template.loader), 277 
get_template() (in module django.template.loader), 276 
app_directories.Loader (class in django.template.loaders), 1382 
cached.Loader (class in django.template.loaders), 1383 
engines (in module django.template.loader), 278 
filesystem.Loader (class in django.template.loaders), 1382 
locmem.Loader (class in django.template.loaders), 1383 
select_template() (in module django.template.loader), 276 

Context (class in django.template), 1373 
Engine (class in django.template), 1371 
Template (class in django.template), 1372 
render() (Template method), 276, 1373 
RequestContext (class in django.template), 1378 

DjangoTemplates (class in django.template.backends.django), 278 
Jinja2 (class in django.template.backends.jinja2), 279 

filter() (django.template.Library method), 563 
inclusion_tag() (django.template.Library method), 568 
simple_tag() (django.template.Library method), 567 
stringfilter() (django.template.defaultfilters method), 564 

debug() (in module django.template.context_processors), 1380 
i18n() (in module django.template.context_processors), 1380 
static() (in module django.template.context_processors), 1380 
tz() (in module django.template.context_processors), 1381 
-->

## Views

<!--
static.serve() (in module django.views), 1418 

defaults.bad_request() (in module django.views), 1420 
defaults.page_not_found() (in module django.views), 1419 
defaults.permission_denied() (in module django.views), 1420 
defaults.server_error() (in module django.views), 1419 

i18n

JavaScriptCatalog (class in django.views.i18n), 463 
JSONCatalog (class in django.views.i18n), 467 
-->

## Generic Class-Based Views

<!--
View (built-in class), 681 
TemplateView (built-in class), 681 
ListView (built-in class), 683 
DetailView (built-in class), 682 
CreateView (built-in class), 685 
UpdateView (built-in class), 686 
DeleteView (built-in class), 687 
RedirectView (built-in class), 682 
FormView (built-in class), 684 

django.views.generic.base.View (built-in class), 647 
django.views.generic.base.TemplateView (built-in class), 648 

django.views.generic.list.BaseListView (built-in class), 653 
django.views.generic.list.ListView (built-in class), 652 

django.views.generic.detail.DetailView (built-in class), 651 

django.views.generic.edit.CreateView (built-in class), 655 
django.views.generic.edit.UpdateView (built-in class), 656 
django.views.generic.edit.DeleteView (built-in class), 657 

django.views.generic.edit.FormView (built-in class), 654 
django.views.generic.edit.ProcessFormView (built-in class), 676 
django.views.generic.base.RedirectView (built-in class), 649 
-->

## View Attributes and Methods

```
http_method_names (django.views.generic.base.View attribute), 648 

as_view() (django.views.generic.base.View class method), 648 
dispatch() (django.views.generic.base.View method), 648 

options() (django.views.generic.base.View method), 648 
http_method_not_allowed() (django.views.generic.base.View method), 648 

get() (django.views.generic.list.BaseListView method), 653 

object (django.views.generic.edit.CreateView attribute), 655 
object (django.views.generic.edit.UpdateView attribute), 656 

template_name_suffix (django.views.generic.edit.CreateView attribute), 655 
template_name_suffix (django.views.generic.edit.DeleteView attribute), 657 
template_name_suffix (django.views.generic.edit.UpdateView attribute), 656 

pattern_name (django.views.generic.base.RedirectView attribute), 650 
permanent (django.views.generic.base.RedirectView attribute), 650 
query_string (django.views.generic.base.RedirectView attribute), 650 
url (django.views.generic.base.RedirectView attribute), 650 

get_redirect_url() (django.views.generic.base.RedirectView method), 650 

get() (django.views.generic.edit.ProcessFormView method), 676 
post() (django.views.generic.edit.ProcessFormView method), 676 
put() (django.views.generic.edit.ProcessFormView method), 676
```

<!--
ArchiveIndexView (built-in class), 688 
TodayArchiveView (built-in class), 693 
DayArchiveView (built-in class), 692 
WeekArchiveView (built-in class), 691 
MonthArchiveView (built-in class), 690 
YearArchiveView (built-in class), 689 
DateDetailView (built-in class), 694 
-->

Generic Dates

```python
BaseDateDetailView (class in django.views.generic.dates), 667 
DateDetailView (class in django.views.generic.dates), 666

DateMixin (class in django.views.generic.dates), 679 
DayMixin (class in django.views.generic.dates), 678 
WeekMixin (class in django.views.generic.dates), 679 
MonthMixin (class in django.views.generic.dates), 677 
YearMixin (class in django.views.generic.dates), 677 

BaseArchiveIndexView (class in django.views.generic.dates), 667 
ArchiveIndexView (class in django.views.generic.dates), 658 

BaseTodayArchiveView (class in django.views.generic.dates), 667 Index 
BaseDayArchiveView (class in django.views.generic.dates), 667 
BaseWeekArchiveView (class in django.views.generic.dates), 667 
BaseMonthArchiveView (class in django.views.generic.dates), 667 
BaseYearArchiveView (class in django.views.generic.dates), 667 

TodayArchiveView (class in django.views.generic.dates), 665
DayArchiveView (class in django.views.generic.dates), 664 
WeekArchiveView (class in django.views.generic.dates), 662 
MonthArchiveView (class in django.views.generic.dates), 660 
YearArchiveView (class in django.views.generic.dates), 659 

get_make_object_list() (YearArchiveView method), 659 
make_object_list (YearArchiveView attribute), 659
```

BaseDateListView

```python
BaseDateListView (class in django.views.generic.dates), 680 

allow_empty (BaseDateListView attribute), 680
date_list_period (BaseDateListView attribute), 680 
get_date_list() (BaseDateListView method), 680 
get_date_list_period() (BaseDateListView method), 680 
get_dated_items() (BaseDateListView method), 680 
get_dated_queryset() (BaseDateListView method), 680 
```

## Client and Response

Client

```python
cookies (Client attribute), 339 
session (Client attribute), 339 

get() (Client method), 333 
post() (Client method), 334 
put() (Client method), 335
delete() (Client method), 335 

head() (Client method), 335  
options() (Client method), 335 
trace() (Client method), 336
patch() (Client method), 335 

login() (Client method), 336 
logout() (Client method), 337 
force_login() (Client method), 336 
```

response.attribute

Response

```python
client (Response attribute), 337 
content (Response attribute), 337 
context (Response attribute), 337 
request (Response attribute), 337 
resolver_match (Response attribute), 338 
status_code (Response attribute), 338 
templates (Response attribute), 338 
wsgi_request (Response attribute), 338 

json() (Response method), 337 
```

## HttpRequest and HttpResponse

<!--
django.http.Http404 (built-in class), 200 
-->

Classes in HTTP

```python
FileResponse (class in django.http), 1263 
HttpRequest (class in django.http), 1249 
HttpResponse (class in django.http), 1257 
HttpResponseBadRequest (class in django.http), 1261 
HttpResponseForbidden (class in django.http), 1261 
HttpResponseGone (class in django.http), 1261 
HttpResponseNotAllowed (class in django.http), 1261 
HttpResponseNotFound (class in django.http), 1261 
HttpResponseNotModified (class in django.http), 1261 
HttpResponsePermanentRedirect (class in django.http), 1260 
HttpResponseRedirect (class in django.http), 1260 
HttpResponseServerError (class in django.http), 1261 
JsonResponse (class in django.http), 1261 
StreamingHttpResponse (class in django.http), 1262 
```

request.attribute
response.attribute

HttpRequest

```python
GET (HttpRequest attribute), 1250 
POST (HttpRequest attribute), 1250 

COOKIES (HttpRequest attribute), 1250 
FILES (HttpRequest attribute), 1250 
META (HttpRequest attribute), 1251 

user (HttpRequest attribute), 1252 

is_ajax() (HttpRequest method), 1254 

body (HttpRequest attribute), 1249 
content_params (HttpRequest attribute), 1250 
content_type (HttpRequest attribute), 1250 
current_app (HttpRequest attribute), 1251 
encoding (HttpRequest attribute), 1250 
method (HttpRequest attribute), 1250 
path (HttpRequest attribute), 1250 
path_info (HttpRequest attribute), 1250 
resolver_match (HttpRequest attribute), 1251 
scheme (HttpRequest attribute), 1249 
session (HttpRequest attribute), 1252 
site (HttpRequest attribute), 1252 
urlconf (HttpRequest attribute), 1251 

get_host() (HttpRequest method), 1252 
get_port() (HttpRequest method), 1253 
get_full_path() (HttpRequest method), 1253 
get_full_path_info() (HttpRequest method), 1253 
build_absolute_uri() (HttpRequest method), 1253 
get_signed_cookie() (HttpRequest method), 1253 
is_secure() (HttpRequest method), 1254 

read() (HttpRequest method), 1254 
readline() (HttpRequest method), 1254 
readlines() (HttpRequest method), 1254 
```

HttpResponse

```python
status_code (HttpResponse attribute), 1258 
content (HttpResponse attribute), 1258 

charset (HttpResponse attribute), 1258 
closed (HttpResponse attribute), 1258 
reason_phrase (HttpResponse attribute), 1258 
streaming (HttpResponse attribute), 1258 

delete_cookie() (HttpResponse method), 1260 
flush() (HttpResponse method), 1260 
getvalue() (HttpResponse method), 1260 
has_header() (HttpResponse method), 1259 
readable() (HttpResponse method), 1260 
seekable() (HttpResponse method), 1260 

set_cookie() (HttpResponse method), 1259 
set_signed_cookie() (HttpResponse method), 1260 

setdefault() (HttpResponse method), 1259 
tell() (HttpResponse method), 1260
writable() (HttpResponse method), 1260 
write() (HttpResponse method), 1260 
writelines() (HttpResponse method), 1260 

__delitem__() (HttpResponse method), 1259 
__getitem__() (HttpResponse method), 1259 
__init__() (HttpResponse method), 1259 
__iter__() (HttpRequest method), 1254 
__setitem__() (HttpResponse method), 1259 
```

HttpResponseRedirect

```python
url (HttpResponseRedirect attribute), 1260 
```

StreamingHttpResponse

```python
reason_phrase (StreamingHttpResponse attribute), 1263 
status_code (StreamingHttpResponse attribute), 1263 
streaming (StreamingHttpResponse attribute), 1263 
streaming_content (StreamingHttpResponse attribute), 1263 
```

## Context

dictionary.method()

Context

```python
get() (Context method), 1376 
pop() (Context method), 1376 
push() (Context method), 1376 
setdefault() (Context method), 1376 
update() (Context method), 1377 
flatten() (Context method), 1377 
```

## QueryDicts

<!--
fromkeys() (django.http.QueryDict class method), 1255 
-->

```python
QueryDict (class in django.http), 1254 
```

"a dictionary-like class customized to deal with multiple values for the same key."

```python
__init__() (QueryDict method), 1255 
_getitem__() (QueryDict method), 1255 
_setitem__() (QueryDict method), 1255 
__contains__() (QueryDict method), 1255 

appendlist() (QueryDict method), 1256 
copy() (QueryDict method), 1256 
dict() (QueryDict method), 1256 
get() (QueryDict method), 1255 
getlist() (QueryDict method), 1256 
items() (QueryDict method), 1255 
lists() (QueryDict method), 1256 
pop() (QueryDict method), 1256 
popitem() (QueryDict method), 1256 
setdefault() (QueryDict method), 1255 
setlist() (QueryDict method), 1256 
setlistdefault() (QueryDict method), 1256 
update() (QueryDict method), 1255 
urlencode() (QueryDict method), 1256 
values() (QueryDict method), 1255 
```

<!--
Deprecated?

* iteritems() (QueryDict method), 1175 
* iterlists() (QueryDict method), 1175 
* itervalues() (QueryDict method), 1175 
-->

## Decorators

<!--
require_GET() (in module django.views.decorators.http), 202 
require_POST() (in module django.views.decorators.http), 202 

condition() (in module django.views.decorators.http), 202 
last_modified() (in module django.views.decorators.http), 202 
require_http_methods() (in module django.views.decorators.http), 202 
require_safe() (in module django.views.decorators.http), 202 

cache_control() (in module django.views.decorators.cache), 203 
never_cache() (in module django.views.decorators.cache), 203 

csrf_exempt() (in module django.views.decorators.csrf), 973 
csrf_protect() (in module django.views.decorators.csrf), 970 
CsrfViewMiddleware (class in django.middleware.csrf), 1093 
ensure_csrf_cookie() (in module django.views.decorators.csrf), 973 
requires_csrf_token() (in module django.views.decorators.csrf), 973 

gzip_page() (in module django.views.decorators.gzip), 203 

sensitive_post_parameters() (in module django.views.decorators.debug), 595 
sensitive_variables() (in module django.views.decorators.debug), 594 

vary_on_cookie() (in module django.views.decorators.vary), 203 
vary_on_headers() (in module django.views.decorators.vary), 203 

decorator_from_middleware() (in module django.utils.decorators), 1401 
decorator_from_middleware_with_args() (in module django.utils.decorators), 1401 
method_decorator() (in module django.utils.decorators), 1401 
-->

## Form Field Methods and Attributes

```python
auto_id (Form attribute), 1035 
changed_data (Form attribute), 1030 
cleaned_data (Form attribute), 1031 
default_renderer (Form attribute), 1038 
error_css_class (Form attribute), 1035 
errors (Form attribute), 1027 
field_order (Form attribute), 1038 
fields (Form attribute), 1030 
initial (Form attribute), 1029 
is_bound (Form attribute), 1026 
label_suffix (Form attribute), 1037 
prefix (Form attribute), 1045 
required_css_class (Form attribute), 1035 
use_required_attribute (Form attribute), 1038 
```

```python
as_p() (Form method), 1033 
as_table() (Form method), 1034 
as_ul() (Form method), 1034 
clean() (Form method), 1027 
is_valid() (Form method), 1027 
```

```python
add_error() (Form method), 1028 
get_initial_for_field() (Form method), 1029 
has_changed() (Form method), 1030 
has_error() (Form method), 1028 
is_multipart() (Form method), 1044 
non_field_errors() (Form method), 1029 
order_fields() (Form method), 1038 
```

<!--
modelform_factory() (in module django.forms.models), 1065 
modelformset_factory() (in module django.forms.models), 1066 

Jinja2 (class in django.forms.renderers), 1067 
TemplatesSetting (class in django.forms.renderers), 1067 

Field (class in django.forms), 1046 
Form (class in django.forms), 1026 
ModelForm (class in django.forms), 250 

CheckboxSelectMultiple (class in django.forms), 1080 
NullBooleanSelect (class in django.forms), 1078 
RadioSelect (class in django.forms), 1078 
Select (class in django.forms), 1078 
SelectMultiple (class in django.forms), 1078 

Textarea (class in django.forms), 1077 

models.BaseInlineFormSet (class in django.forms), 266 
models.BaseModelFormSet (class in django.forms), 260 

BaseFormSet (class in django.forms.formsets), 238 

can_delete (BaseFormSet attribute), 245 
can_order (BaseFormSet attribute), 244 
total_error_count() (BaseFormSet method), 241 

set_headers() (FileResponse method), 1263 

srid (Field attribute), 809 

as_data() (Form.errors method), 1028 
as_json() (Form.errors method), 1028 
get_json_data() (Form.errors method), 1028 

DjangoTemplates (class in django.forms.renderers), 1067 

BaseModelFormSet
changed_objects (models.BaseModelFormSet attribute), 263 
deleted_objects (models.BaseModelFormSet attribute), 263 
new_objects (models.BaseModelFormSet attribute), 263 

formsets
formset_factory() (in module django.forms.formsets), 1066 
inlineformset_factory() (in module django.forms.models), 1066 
-->

## Model and Form Fields

```python
Field (class in django.db.models), 1125 
```

Model Fields Shared with Form Fields

```python
BooleanField (class in django.db.models), 1108 
CharField (class in django.db.models), 1108 
DateField (class in django.db.models), 1108 
DateTimeField (class in django.db.models), 1109 
DecimalField (class in django.db.models), 1109 
DurationField (class in django.db.models), 1110 
EmailField (class in django.db.models), 1110 
FileField (class in django.db.models), 1110 
FilePathField (class in django.db.models), 1113 
FloatField (class in django.db.models), 1114 
GenericIPAddressField (class in django.db.models), 1115 
ImageField (class in django.db.models), 1114 
IntegerField (class in django.db.models), 1115 
NullBooleanField (class in django.db.models), 1115 
SlugField (class in django.db.models), 1116 
TimeField (class in django.db.models), 1116 
URLField (class in django.db.models), 1116 
UUIDField (class in django.db.models), 1117 
```

Not Shared

```python
Fields
AutoField (class in django.db.models), 1107 
BigAutoField (class in django.db.models), 1107 
BigIntegerField (class in django.db.models), 1107 
BinaryField (class in django.db.models), 1107 
PositiveIntegerField (class in django.db.models), 1115 
PositiveSmallIntegerField (class in django.db.models), 1115 
SmallIntegerField (class in django.db.models), 1116 
TextField (class in django.db.models), 1116 
```

Form Fields Shared with Model Fields

```python
BooleanField (class in django.forms), 1051 
CharField (class in django.forms), 1051 
DateField (class in django.forms), 1053 
DateTimeField (class in django.forms), 1053 
DecimalField (class in django.forms), 1054 
DurationField (class in django.forms), 1055 
EmailField (class in django.forms), 1055 
FileField (class in django.forms), 1055 
FilePathField (class in django.forms), 1056 
FloatField (class in django.forms), 1056 
GenericIPAddressField (class in django.forms), 1057 
ImageField (class in django.forms), 1056 
IntegerField (class in django.forms), 1057 
NullBooleanField (class in django.forms), 1058 
SlugField (class in django.forms), 1059 
TimeField (class in django.forms), 1059 
URLField (class in django.forms), 1060 
UUIDField (class in django.forms), 1060 
```

Not Shared

```python
BoundField (class in django.forms), 1040 
ChoiceField (class in django.forms), 1052 
ComboField (class in django.forms), 1060 
ModelChoiceField (class in django.forms), 1063 
ModelMultipleChoiceField (class in django.forms), 1064 
MultipleChoiceField (class in django.forms), 1058 
MultiValueField (class in django.forms), 1061 
RegexField (class in django.forms), 1059 
SplitDateTimeField (class in django.forms), 1062 
TypedChoiceField (class in django.forms), 1052 
TypedMultipleChoiceField (class in django.forms), 1058 
```

Form Input

```python
CheckboxInput (class in django.forms), 1078 
ClearableFileInput (class in django.forms), 1081 
DateInput (class in django.forms), 1076 
DateTimeInput (class in django.forms), 1077 
EmailInput (class in django.forms), 1075 
FileInput (class in django.forms), 1080 
NumberInput (class in django.forms), 1075 
PasswordInput (class in django.forms), 1076 
TextInput (class in django.forms), 1075 
TimeInput (class in django.forms), 1077 
URLInput (class in django.forms), 1076 
```

Hidden Input

```python
HiddenInput (class in django.forms), 1076 
MultipleHiddenInput (class in django.forms), 1081 
```

GenericIPAddressField

```python
unpack_ipv4 (GenericIPAddressField attribute), 1058, 1115 
```

Bound Field

```python
auto_id (BoundField attribute), 1040 
data (BoundField attribute), 1040 
errors (BoundField attribute), 1040 
field (BoundField attribute), 1041 
form (BoundField attribute), 1041 
help_text (BoundField attribute), 1041 
html_name (BoundField attribute), 1041 
id_for_label (BoundField attribute), 1041 
is_hidden (BoundField attribute), 1041 
label (BoundField attribute), 1041 
name (BoundField attribute), 1041 

as_hidden() (BoundField method), 1042 
as_widget() (BoundField method), 1042 
css_classes() (BoundField method), 1042 
label_tag() (BoundField method), 1042 
value() (BoundField method), 1042 
```




<!--
Common to Django, same as above

### Comparison Operators: Greater Than, Greater Than or Equal, Less Than, Less Than or Equal

```> >= < <=```

### Equality Operators: Equivalent, Not equivalent

```== !=```

### Assignment Operators

Assignment 

```=```

### Identity Operators

True if same object/identify (id)

```is``` 

True if different object/identity (id)

```is not```

### Membership Operators

```
in
not in
```

### Logical Operators

```
and
or
not
```
-->

## Django Confirmation and Negation

<!--
exists(), none, null, if not, etc.

ifequal and ifnotequal


QuerySet Method
* none()

Field Look-Up Type
* isnull

Template Tag
* for ... empty

Template Filter
* default
* default_if_none
-->


## Django Tags and Filters

#### cycle Example

Cycle is particularly useful in a loop

```python
{% for object in list %}
    {% cycle %}
```

#### resetcycle Example


#### firstof Example

```python
{% firstof %}
```

Equivalent

```python
{% if %}
    {{ do something }}
{% elif %}
    {{ do something }}
{% elif %}
    {{ do something }}
{% endif %}
```

#### for Example

<!--
See also: list of lists, dot operator clarification and forloop variables table
-->

List

```python
{% for object in list %}
    <li>{{ object.variable }}</li>
{% endfor %}
```

Dictionary

```python
{% for key, value in dictionary.items %}
    {{ key }}: {{ value }}
{% endfor %}
```

#### for ... empty Example

"text is displayed if the given array is empty or could not be found"

```python
{% for object in list %}
    <li>{{ object.variable }}</li>
{% empty %}
    <li>Message</li>
{% endfor %}
```

Alternate

```python
{% if list %}
  {% for object in list %}
    <li>{{ object.variable }}</li>
  {% endfor %}
{% else %}
  <li>Message</li>
{% endif %}
```

#### if Example

<!--
"The {% if %} tag evaluates a variable, and if that variable is “true” (i.e. exists, is not empty, and is not a false boolean value) the contents of the block are output:"

Resume

Filters
-->


#### if- Boolean Operators and Complex Expressions

<!--
https://docs.djangoproject.com/en/2.0/ref/templates/builtins/#boolean-operators

"if tags may use and, or, or not to test a number of variables or to negate a given variable:"
-->




### Other Common Template Tags

<!--
Internationalization tags and filters
i18n
l10n
tz

Other tags and filters libraries
django.contrib.humanize
-->

<!--
Template Filters
https://docs.djangoproject.com/en/2.0/ref/templates/builtins/

https://docs.djangoproject.com/en/2.0/ref/templates/builtins/#default
-->


## Django QuerySet

<!--
https://docs.djangoproject.com/en/2.0/ref/models/querysets/#when-querysets-are-evaluated

QuerySet API reference
When QuerySets are evaluated
Pickling QuerySets
QuerySet API

https://www.quora.com/Why-do-we-use-a-double-underscore-when-using-a-model-field-in-Django

https://docs.djangoproject.com/en/2.0/topics/db/queries/#field-lookups
https://docs.djangoproject.com/en/2.0/topics/db/queries/#other-queryset-methods
https://docs.djangoproject.com/en/2.0/howto/custom-lookups/
-->

QuerySet (class in django.db.models.query)

Iterator and Aggregate
* iterator()
    With server-side cursors
    Without server-side cursors
* aggregate() 

<!--
Query-related tools
Q() objects
Prefetch() objects
prefetch_related_objects()
FilteredRelation() objects

https://docs.djangoproject.com/en/2.0/ref/models/expressions/
https://docs.djangoproject.com/en/2.0/ref/models/querysets/#id5

Aggregation functions
expression
output_field
filter
**extra
Avg
Count
Max
Min
StdDev
Sum
Variance
-->

<!--
Old

## Django Field Look-Up Types

(See also SQLite Users)

https://docs.djangoproject.com/en/2.0/ref/models/querysets/#isnull

"Takes either True or False, which correspond to SQL queries of IS NULL and IS NOT NULL, respectively."
-->

## Django Field Look-Up Types- GEO

* exact, 783, 1131 




## Modules

Postgres

```python
django.contrib.postgres (module), 898 
django.contrib.postgres.aggregates (module), 898 
django.contrib.postgres.indexes (module), 919 
django.contrib.postgres.validators (module), 925 
```

Database

```python
django.db (module), 84 
django.db.backends (module), 1321 
django.db.backends.base.schema (module), 1264 
django.db.transaction (module), 146 
```

Database Migrations

```python
django.db.migrations (module), 312 
django.db.migrations.operations (module), 1094 
```

Test

```python
django.test (module), 326 
django.test.signals (module), 1321 
django.test.utils (module), 365 
```

Core Exceptions

```python
django.core.exceptions (module), 1014 
```

Core Checks

```python
django.core.checks (module), 534 
```

Core Validators

```python
django.core.validators (module), 1414 
```

Core Management

```python
django.core.management (module), 541 
```

Middleware

```python
django.middleware (module), 1088 
django.middleware.clickjacking (module), 696, 1093 
django.middleware.common (module), 1089 
django.middleware.locale (module), 1090 
django.middleware.security (module), 1090 
```

Middleware + Decorator

```python
django.middleware.cache (module), 1088 
django.views.decorators.cache (module), 203 
django.middleware.csrf (module), 968, 1093 
django.views.decorators.csrf (module), 970 
django.middleware.gzip (module), 1089 
django.views.decorators.gzip (module), 203 
django.middleware.http (module), 1090 
django.views.decorators.http (module), 202 
```

Decorators

```python
django.views.decorators.vary (module), 203 
```

Admin

```python
django.contrib.admin (module), 698 
django.contrib.admindocs (module), 706 
```

Database Models

```python
django.db.models (module), 84 
django.db.models.fields (module), 1101 
django.db.models.fields.related (module), 1117 
django.db.models.functions (module), 1231 
django.db.models.indexes (module), 1128 
django.db.models.lookups (module), 1207 
django.db.models.options (module), 1129 
django.db.models.signals (module), 1314 
```

Forms

```python
django.forms (module), 1026 
django.forms.fields (module), 1046 
django.forms.formsets (module), 238, 1066 
django.forms.models (module), 250, 1065 
django.forms.renderers (module), 1067 
django.forms.widgets (module), 1068 
```

Apps

```python
django.apps (module), 629 
```

Conf URLs

```python
django.urls (module), 1394 
django.urls.conf (module), 1397 
django.conf.urls (module), 1398 
```

Contrib Redirects

```python
django.contrib.redirects (module), 926 
```

Shortcuts

```python
django.shortcuts (module), 207 
```

HTTP

```python
django.http (module), 1249 
```

Static Files

```python
django.contrib.staticfiles (module), 942 
```

Template

```python
django.template (module), 274 
django.template.backends (module), 278 
django.template.backends.django (module), 278 
django.template.backends.jinja2 (module), 279 
django.template.loader (module), 276 
django.template.response (module), 1385 
```

Views

```python
django.views (module), 1418 
django.views.generic.dates (module), 658 
django.views.i18n (module), 463 
```

Contrib Auth

```python
django.contrib.auth (module), 413 
django.contrib.auth.backends (module), 760 
django.contrib.auth.forms (module), 385 
django.contrib.auth.hashers (module), 394 
django.contrib.auth.middleware (module), 1093 
django.contrib.auth.password_validation (module), 394 
django.contrib.auth.signals (module), 760 
django.contrib.auth.views (module), 378 
```

Sites

```python
django.contrib.sites (module), 935 
django.contrib.sites.middleware (module), 1092 
```

Core Signals

```python
django.core.signals (module), 1320 
```

Dispatch

```python
django.dispatch (module), 530 
```

Contrib Sessions

```python
django.contrib.sessions (module), 216 
django.contrib.sessions.middleware (module), 1092 
```

Core Files

```python
django.core.files (module), 1018 
django.core.files.storage (module), 1020 
django.core.files.uploadedfile (module), 1023 
django.core.files.uploadhandler (module), 1024 
```

Contrib Messages

```python
django.contrib.messages (module), 891 
django.contrib.messages.middleware (module), 1090 
```

Contrib Content Types

```python
django.contrib.contenttypes (module), 762 
django.contrib.contenttypes.admin (module), 768 
django.contrib.contenttypes.fields (module), 765 
django.contrib.contenttypes.forms (module), 768 
```

Core Mail

```python
django.core.mail (module), 439 
```

Conf URLs i18n, Contrib Humanize, Utils Timezone, Utils Translation

```python
django.conf.urls.i18n (module), 468 
django.contrib.humanize (module), 889 
django.utils.timezone (module), 1410 
django.utils.translation (module), 449, 1412 
```

Sitemaps

```python
django.contrib.sitemaps (module), 927 
```

Flat Pages

```python
django.contrib.flatpages (module), 769 
```

Core Paginator

```python
django.core.paginator (module), 504 
```

Contrib Syndication and Utils Feedgenerator

```python
django.contrib.syndication (module), 949 
django.utils.feedgenerator (module), 1403 
```

Core Signing

```python
django.core.signing (module), 436 
```

Utils

```python
django.utils (module), 1399 
django.utils.cache (module), 1400 
django.utils.dateparse (module), 1401 
django.utils.decorators (module), 1401 
django.utils.encoding (module), 1402 
django.utils.functional (module), 1405 
django.utils.html (module), 1407 
django.utils.http (module), 1408 
django.utils.log (module), 493 
django.utils.module_loading (module), 1409 
django.utils.safestring (module), 1409 
django.utils.text (module), 1410 
```

## ```django-admin``` Commands

<!--
https://docs.djangoproject.com/en/2.1/howto/custom-management-commands
https://docs.djangoproject.com/en/2.1/ref/django-admin/
-->

```python
help, 989 
version, 989 
startapp, 1004 
startproject, 1005 
createsuperuser, 1009 
loaddata, 994 
makemigrations, 998 
migrate, 999 
runserver, 944, 1000 
collectstatic, 942 
```

```python
test, 1006 
testserver, 1007 

showmigrations, 1002 
squashmigrations, 1004 

sqlflush, 1003 
sqlmigrate, 1003 
sqlsequencereset, 1003 

makemessages, 997 
compilemessages, 990 

changepassword, 1008 
check, 990 
clearsessions, 1010 
createcachetable, 991 
dbshell, 991 
diffsettings, 992 
dumpdata, 992 
findstatic, 944 
flush, 993 
inspectdb, 993 
ogrinspect, 883 
ping_google, 935 
remove_stale_contenttypes, 1009 
sendtestemail, 1001 
shell, 1002 
```

<!--
startproject command line option 
–extension EXTENSIONS, -e EXTENSIONS, 1005 
–name FILES, -n FILES, 1005 
–template TEMPLATE, 1005 

startapp command line option 
–extension EXTENSIONS, -e EXTENSIONS, 1004 
–name FILES, -n FILES, 1005 
–template TEMPLATE, 1004 

createsuperuser command line option 
–database DATABASE, 1009 
–email EMAIL, 1009 
–username USERNAME, 1009 

loaddata command line option 
–app APP_LABEL, 994 
–database DATABASE, 994 
–exclude EXCLUDE, -e EXCLUDE, 994 
–format FORMAT, 994 
–ignorenonexistent, -i, 994 

migrate command line option 
–database DATABASE, 999 
–fake, 999 
–fake-initial, 999 
–noinput, –no-input, 999 
–run-syncdb, 999 

makemigrations command line option 
–check, 999 
–dry-run, 999 
–empty, 998 
–merge, 999 
–name NAME, -n NAME, 999 
–noinput, –no-input, 998 

runserver command line option 
–insecure, 945 
–ipv6, -6, 1000 –noreload, 1000 
–nostatic, 944 
–nothreading, 1000 

collectstatic command line option 
–clear, -c, 943 
–dry-run, -n, 943 
–ignore PATTERN, -i PATTERN, 943 
–link, -l, 943 
–no-default-ignore, 943 
–no-post-process, 943 
–noinput, –no-input, 943 

testserver command line option 
–addrport ADDRPORT, 1008 
–noinput, –no-input, 1008 

test command line option 
–debug-mode, 1006 
–debug-sql, -d, 1006 
–exclude-tag EXCLUDE_TAGS, 1007 
–failfast, 1006 
–keepdb, -k, 1006 
–noinput, –no-input, 1006 
–parallel [N], 1006 
–reverse, -r, 1006 
–tag TAGS, 1007 
–testrunner TESTRUNNER, 1006 

showmigrations command line option 
–database DATABASE, 1003 
–list, -l, 1002 
–plan, -p, 1003 

squashmigrations command line option –no-optimize, 1004
 –noinput, –no-input, 1004 
–squashed-name SQUASHED_NAME, 1004 

sqlflush command line option 
–database DATABASE, 1003 

sqlmigrate command line option –backwards, 1003 
–database DATABASE, 1003 

sqlsequencereset command line option –database DATABASE, 1003 

makemessages command line option 
–add-location [{full,file,never}], 998 
–all, -a, 997 
–domain DOMAIN, -d DOMAIN, 997 
–exclude EXCLUDE, -x EXCLUDE, 997 
–extension EXTENSIONS, -e EXTENSIONS, 997
–ignore PATTERN, -i PATTERN, 997 
–keep-pot, 998 
–locale LOCALE, -l LOCALE, 997 
–no-default-ignore, 998 
–no-location, 998 
–no-wrap, 998 
–symlinks, -s, 997

compilemessages command line option 
–exclude EXCLUDE, -x EXCLUDE, 990 
–locale LOCALE, -l LOCALE, 990 
–use-fuzzy, -f, 991 



changepassword command line option 
–database DATABASE, 1008 

check command line option 
–deploy, 990 
–fail-level {CRITICAL,ERROR,WARNING,INFO,DEBUG}, 990 
–list-tags, 990 
–tag TAGS, -t TAGS, 990 

clearsessions?

command line option 
–no-color, 1011 
–pythonpath PYTHONPATH, 1010 
–settings SETTINGS, 1010 
–traceback, 1011 
–verbosity {0,1,2,3}, -v {0,1,2,3}, 1011 

createcachetable command line option 
–database DATABASE, 991 
–dry-run, 991 CreateExtension (class in django.contrib.postgres.operations), 921 

dbshell command line option 
–database DATABASE, 991 

diffsettings command line option 
–all, 992 
–default MODULE, 992 
–output {hash,unified}, 992 

dumpdata command line option 
–all, -a, 992 
–database DATABASE, 992 
–exclude EXCLUDE, -e EXCLUDE, 992 
–format FORMAT, 992 
–indent INDENT, 992 
–natural-foreign, 993 
–natural-primary, 993 
–output OUTPUT, -o OUTPUT, 993 
–pks PRIMARY_KEYS, 993 

findstatic –first findstatic command line option, 944 
findstatic command line option 
findstatic –first, 944 

flush command line option 
–database DATABASE, 993 
–noinput, –no-input, 993 

inspectdb command line option 
–database DATABASE, 994 
–include-views, 994 

shell command line option 
–command COMMAND, -c COMMAND, 1002 
–interface {ipython,bpython,python}, -i {ipython,bpython,python}, 1002 
–nostartup, 1002 

sendtestemail command line option 
–admins, 1002 
–managers, 1001 

remove_stale_contenttypes command line option 
–database DATABASE, 1009 
-->

## ```DJANGO_SETTINGS_MODULE```

<!--
https://docs.djangoproject.com/en/2.1/ref/settings/

Does not include PostGIS, GEOIP, GEOS, GDAL

ABSOLUTE_URL_OVERRIDES setting, 1267
"app_label.model_name"
-->

<!--
Pinax Common

PROJECT_ROOT = os.path.abspath(os.path.join(os.path.dirname(__file__), os.pardir))
PACKAGE_ROOT = os.path.abspath(os.path.dirname(__file__))
BASE_DIR = PACKAGE_ROOT

FIXTURE_DIRS
EMAIL_BACKEND
AUTHENTICATION_BACKENDS
-->

```python
ABSOLUTE_URL_OVERRIDES setting, 1267 
FORM_RENDERER setting, 1287 
MIGRATION_MODULES setting, 1292  
```

Common

```python
DEBUG setting, 1281 
DATABASES setting, 1272 
ALLOWED_HOSTS setting, 1267 
TIME_ZONE setting, 1300 
LANGUAGE_CODE setting, 1289 
SITE_ID setting, 1308 
USE_I18N setting, 1300 
USE_L10N setting, 1300 
USE_TZ setting, 1301 
MEDIA_ROOT setting, 1291 
MEDIA_URL setting, 1291 
STATIC_ROOT setting, 1308 
STATIC_URL setting, 1308 
STATICFILES_DIRS setting, 1308 
STATICFILES_STORAGE setting, 1309 
STATICFILES_FINDERS setting, 1309 
SECRET_KEY setting, 1293 
TEMPLATES setting, 1297 
BACKEND setting, 1298 
DIRS setting, 1298 
APP_DIRS setting, 1298 
OPTIONS setting, 1298 
MIDDLEWARE setting, 1292 
ROOT_URLCONF setting, 1293 
WSGI_APPLICATION setting, 1301 
INSTALLED_APPS setting, 1288 
LOGGING setting, 1291 
FIXTURE_DIRS setting, 1286 
EMAIL_BACKEND setting, 1283 
AUTHENTICATION_BACKENDS setting, 1302 
```

Admin and Manager

```python
ADMINS setting, 1267 
MANAGERS setting, 1291 
```

Database

```python
HOST setting, 1273 
NAME setting, 1274 
PORT setting, 1274 
OPTIONS setting, 1274

CONN_MAX_AGE setting, 1274 
USER setting, 1275 
```

Database

```python
ATOMIC_REQUESTS setting, 1273 
AUTOCOMMIT setting, 1273 
DISABLE_SERVER_SIDE_CURSORS setting, 1275 

ENGINE setting, 1273 
TEST setting, 1275 
TIME_ZONE setting, 1274 

DATABASE_ROUTERS setting, 1279 
DEFAULT_INDEX_TABLESPACE setting, 1283 
DEFAULT_TABLESPACE setting, 1283 
```

Error Reporting

```python
DEFAULT_EXCEPTION_REPORTER_FILTER setting, 1282 
SILENCED_SYSTEM_CHECKS setting, 1297 
IGNORABLE_404_URLS setting, 1288 
```

More Debug

```python
DEBUG_PROPAGATE_EXCEPTIONS setting, 1282 
```

Test Settings

```python
TEST_CHARSET setting, 1275 
TEST_COLLATION setting, 1276 
TEST_CREATE setting, 1277 
TEST_DEPENDENCIES setting, 1276 
TEST_MIRROR setting, 1276 
TEST_NAME setting, 1276 
TEST_NON_SERIALIZED_APPS setting, 1299 
TEST_RUNNER setting, 1299 
TEST_SERIALIZE setting, 1276 
```

PostgreSQL Setting

```python
TEST_TEMPLATE setting, 1276 
```

Logging

```python
LOGGING_CONFIG setting, 1291 
```

HTTP and Security

<!--
https://www.owasp.org
https://docs.djangoproject.com/en/2.1/ref/middleware/#django.middleware.security.SecurityMiddleware
-->

```python
SECURE_BROWSER_XSS_FILTER setting, 1294 
SECURE_CONTENT_TYPE_NOSNIFF setting, 1294 
SECURE_HSTS_INCLUDE_SUBDOMAINS setting, 1294 
SECURE_HSTS_PRELOAD setting, 1294 
SECURE_HSTS_SECONDS setting, 1295 
SECURE_PROXY_SSL_HEADER setting, 1295 
SECURE_REDIRECT_EXEMPT setting, 1296 
SECURE_SSL_HOST setting, 1296 
SECURE_SSL_REDIRECT setting, 1296 

DEFAULT_CHARSET setting, 1282 
DEFAULT_CONTENT_TYPE setting, 1282 (deprecated)
DISALLOWED_USER_AGENTS setting, 1283 
FORCE_SCRIPT_NAME setting, 1287 
INTERNAL_IPS setting, 1289 
SIGNING_BACKEND setting, 1297 
USE_X_FORWARDED_HOST setting, 1301 
USE_X_FORWARDED_PORT setting, 1301 
```

CSRF Settings

<!--
https://www.owasp.org/index.php/Cross-Site_Request_Forgery_(CSRF)

X_FRAME_OPTIONS setting, 1302 
-->

```python
CSRF_COOKIE_AGE setting, 1270 
CSRF_COOKIE_DOMAIN setting, 1270 
CSRF_COOKIE_HTTPONLY setting, 1271 
CSRF_COOKIE_NAME setting, 1271 
CSRF_COOKIE_PATH setting, 1271 
CSRF_COOKIE_SAMESITE setting, 1271 
CSRF_COOKIE_SECURE setting, 1271 
CSRF_FAILURE_VIEW setting, 1272 
CSRF_HEADER_NAME setting, 1272 
CSRF_TRUSTED_ORIGINS setting, 1272 
CSRF_USE_SESSIONS setting, 1271 
```

Sessions and Cookie Settings

```python
SESSION_CACHE_ALIAS setting, 1305 
SESSION_COOKIE_AGE setting, 1305 
SESSION_COOKIE_DOMAIN setting, 1305 
SESSION_COOKIE_HTTPONLY setting, 1306 
SESSION_COOKIE_NAME setting, 1306 
SESSION_COOKIE_PATH setting, 1306 
SESSION_COOKIE_SAMESITE setting, 1306 
SESSION_COOKIE_SECURE setting, 1306 
SESSION_ENGINE setting, 1307 
SESSION_EXPIRE_AT_BROWSER_CLOSE setting, 1307 
SESSION_FILE_PATH setting, 1307 
SESSION_SAVE_EVERY_REQUEST setting, 1307 
SESSION_SERIALIZER setting, 1307 
```

File Upload

```python
DEFAULT_FILE_STORAGE setting, 1282 
FILE_CHARSET setting, 1285 
FILE_UPLOAD_DIRECTORY_PERMISSIONS setting, 1285 
FILE_UPLOAD_HANDLERS setting, 1285 
FILE_UPLOAD_MAX_MEMORY_SIZE setting, 1285 
FILE_UPLOAD_PERMISSIONS setting, 1286 
FILE_UPLOAD_TEMP_DIR setting, 1286 
```

Template Settings

```python
NAME setting, 1298 
```

URLs

```python
APPEND_SLASH setting, 1268 
PREPEND_WWW setting, 1293 
```

Auth

```python
AUTH_USER_MODEL setting, 1302 
AUTH_PASSWORD_VALIDATORS setting, 1304 
```

Login and Logout

```python
LOGIN_URL setting, 1303 
LOGIN_REDIRECT_URL setting, 1303 
LOGOUT_REDIRECT_URL setting, 1303 
```

Password

```python
PASSWORD setting, 1274 
PASSWORD_RESET_TIMEOUT_DAYS setting, 1303 
PASSWORD_HASHERS setting, 1303 
```

Messages

```python
MESSAGE_LEVEL setting, 1304 
MESSAGE_STORAGE setting, 1304 
MESSAGE_TAGS setting, 1304 
```

Cache Settings

```python
CACHES setting, 1268 
BACKEND setting, 1268 
KEY_FUNCTION setting, 1269 
KEY_PREFIX setting, 1269 
LOCATION setting, 1269 
OPTIONS setting, 1269 
TIMEOUT setting, 1269 
VERSION setting, 1269 
```

Cache Middleware Settings

```python
CACHE_MIDDLEWARE_ALIAS setting, 1270 
CACHE_MIDDLEWARE_KEY_PREFIX setting, 1270 
CACHE_MIDDLEWARE_SECONDS setting, 1270 
```

Serialization (and Sessions?)

```python
SERIALIZATION_MODULES setting, 1296 
```

Globalization- Language

```python
LANGUAGES setting, 1290 
LANGUAGE_COOKIE_AGE setting, 1289 
LANGUAGE_COOKIE_DOMAIN setting, 1289 
LANGUAGE_COOKIE_NAME setting, 1290 
LANGUAGE_COOKIE_PATH setting, 1290 
```

Globalization- ```USE_L10N = True``` takes precedence over:
    
```python
DATE_FORMAT setting, 1280 
DATE_INPUT_FORMATS setting, 1280 
DATETIME_FORMAT setting, 1280 
DATETIME_INPUT_FORMATS setting, 1280 
DECIMAL_SEPARATOR setting, 1282 
NUMBER_GROUPING setting, 1293 
SHORT_DATE_FORMAT setting, 1297 
SHORT_DATETIME_FORMAT setting, 1297 
THOUSAND_SEPARATOR setting, 1299 
TIME_FORMAT setting, 1299 
TIME_INPUT_FORMATS setting, 1299 
USE_THOUSAND_SEPARATOR setting, 1301 
FIRST_DAY_OF_WEEK setting, 1286 
MONTH_DAY_FORMAT setting, 1292 
YEAR_MONTH_FORMAT setting, 1302 
```

Globalization- More

```python
FORMAT_MODULE_PATH setting, 1287 
LOCALE_PATHS setting, 1290  
```

Email

```python
DEFAULT_FROM_EMAIL setting, 1283 
EMAIL_FILE_PATH setting, 1283 
EMAIL_HOST setting, 1283 
EMAIL_HOST_PASSWORD setting, 1283 
EMAIL_HOST_USER setting, 1284 
EMAIL_PORT setting, 1284 
EMAIL_SSL_CERTFILE setting, 1284 
EMAIL_SSL_KEYFILE setting, 1285 
EMAIL_SUBJECT_PREFIX setting, 1284 
EMAIL_TIMEOUT setting, 1285 
EMAIL_USE_LOCALTIME setting, 1284 
EMAIL_USE_SSL setting, 1284 
EMAIL_USE_TLS setting, 1284
SERVER_EMAIL setting, 1296 
```

Data Upload

```python
DATA_UPLOAD_MAX_MEMORY_SIZE setting, 1279 
DATA_UPLOAD_MAX_NUMBER_FIELDS setting, 1279 
```

Oracle-Specific Settings

```python
TEST_USER setting, 1277 
TEST_USER_CREATE setting, 1277 
TEST_PASSWD setting, 1277 
TEST_TBLSPACE setting, 1277 
TEST_TBLSPACE_TMP setting, 1277 
DATAFILE setting, 1278 
DATAFILE_TMP setting, 1278 
DATAFILE_SIZE setting, 1278 
DATAFILE_TMP_SIZE setting, 1278 
DATAFILE_EXTSIZE setting, 1279 
DATAFILE_TMP_EXTSIZE setting, 1279 
DATAFILE_MAXSIZE setting, 1278 
DATAFILE_TMP_MAXSIZE setting, 1278 
```

## Environmental Variables

<!--
environment variable DJANGO_SETTINGS_MODULE, 526, 530, 586, 939, 988, 989, 1589 
-->

```python
PYTHONPATH, 1589 
PYTHONSTARTUP, 1002 
PYTHONWARNINGS, 592 
```

## Configs

```python
setup() (in module django), 634 
django.conf.settings.configure() (built-in function), 528 
```

<!--
raw() (Manager method), 141 

__init__() (requests.RequestSite method), 941 
-->


## AppConfig and Apps

```python
AppConfig (class in django.apps), 631 
apps (in module django.apps), 633 
```

AppConfig

```python
label (AppConfig attribute), 631 
models_module (AppConfig attribute), 632 
module (AppConfig attribute), 632 
name (AppConfig attribute), 631 
path (AppConfig attribute), 631 
verbose_name (AppConfig attribute), 631 

get_model() (AppConfig method), 632 
get_models() (AppConfig method), 632 
ready() (AppConfig method), 632 
```

apps

```python
get_app_config() (apps method), 633 
get_app_configs() (apps method), 633 
get_model() (apps method), 633 
is_installed() (apps method), 633 
ready (apps attribute), 633 
```

## Middleware

<!--
BrokenLinkEmailsMiddleware (class in django.middleware.common), 1089 
CommonMiddleware (class in django.middleware.common), 1089 
ConditionalGetMiddleware (class in django.middleware.http), 1090 
FetchFromCacheMiddleware (class in django.middleware.cache), 1088 
GZipMiddleware (class in django.middleware.gzip), 1089 
LocaleMiddleware (class in django.middleware.locale), 1090 
SecurityMiddleware (class in django.middleware.security), 1090 
UpdateCacheMiddleware (class in django.middleware.cache), 1088 
XFrameOptionsMiddleware (class in django.middleware.clickjacking), 1093 

CurrentSiteMiddleware (class in django.contrib.sites.middleware), 1092 
MessageMiddleware (class in django.contrib.messages.middleware), 1090 
SessionMiddleware (class in django.contrib.sessions.middleware), 1092 

middleware.RedirectFallbackMiddleware (class in django.contrib.redirects), 927 
models.Redirect (class in django.contrib.redirects), 927 
response_gone_class (middleware.RedirectFallbackMiddleware attribute), 927 
response_redirect_class (middleware.RedirectFallbackMiddleware attribute), 927 

response_redirect_class (CommonMiddleware attribute), 1089 
response_redirect_class (LocaleMiddleware attribute), 1090 

django.utils.deprecation.MiddlewareMixin (built-in class), 215 
-->

## Static Files

<!--
manifest_strict (storage.ManifestStaticFilesStorage attribute), 946 
max_post_process_passes (storage.ManifestStaticFilesStorage attribute), 946 

post_process() (storage.StaticFilesStorage method), 945 

storage.CachedStaticFilesStorage (class in django.contrib.staticfiles), 946 
storage.ManifestFilesMixin (class in django.contrib.staticfiles), 947 
storage.ManifestStaticFilesStorage (class in django.contrib.staticfiles), 945 
storage.StaticFilesStorage (class in django.contrib.staticfiles), 945 

testing.StaticLiveServerTestCase (class in django.contrib.staticfiles), 948 

urls.staticfiles_urlpatterns() (in module django.contrib.staticfiles), 948 
views.serve() (in module django.contrib.staticfiles), 947 
-->


## Model Admin

Classes

```python
AdminSite (class in django.contrib.admin), 748 

apps.AdminConfig (class in django.contrib.admin), 711 
apps.SimpleAdminConfig (class in django.contrib.admin), 711 

autodiscover() (in module django.contrib.admin), 711 
register() (in module django.contrib.admin), 710 

ModelAdmin (class in django.contrib.admin), 710 
InlineModelAdmin (class in django.contrib.admin), 740 

StackedInline (class in django.contrib.admin), 740 
TabularInline (class in django.contrib.admin), 740 

models.LogEntry (class in django.contrib.admin), 753 

GenericInlineModelAdmin (class in django.contrib.contenttypes.admin), 768 
GenericStackedInline (class in django.contrib.contenttypes.admin), 768 
GenericTabularInline (class in django.contrib.contenttypes.admin), 768 

staff_member_required() (in module django.contrib.admin.views.decorators), 755 
```

AdminSite

```python
app_index_template (AdminSite attribute), 749 
empty_value_display (AdminSite attribute), 749 
index_template (AdminSite attribute), 749 
index_title (AdminSite attribute), 749
login_form (AdminSite attribute), 749 
login_template (AdminSite attribute), 749 
logout_template (AdminSite attribute), 749 
password_change_done_template (AdminSite attribute), 749 
password_change_template (AdminSite attribute), 749 
site_header (AdminSite attribute), 748 
site_title (AdminSite attribute), 748 
site_url (AdminSite attribute), 748 

add_action() (AdminSite method), 704 
disable_action() (AdminSite method), 704 
each_context() (AdminSite method), 749 
has_permission() (AdminSite method), 750 
register() (AdminSite method), 750 
```

ModelAdmin

```python
actions (ModelAdmin attribute), 711 
actions_on_bottom (ModelAdmin attribute), 711 
actions_on_top (ModelAdmin attribute), 711 
actions_selection_counter (ModelAdmin attribute), 711 
add_form_template (ModelAdmin attribute), 729 
autocomplete_fields (ModelAdmin attribute), 725 
change_form_template (ModelAdmin attribute), 729 
change_list_template (ModelAdmin attribute), 729 
date_hierarchy (ModelAdmin attribute), 711 
delete_confirmation_template (ModelAdmin attribute), 729 
delete_selected_confirmation_template (ModelAdmin attribute), 729 
empty_value_display (ModelAdmin attribute), 712 
exclude (ModelAdmin attribute), 712 
fields (ModelAdmin attribute), 713 
fieldsets (ModelAdmin attribute), 713 
filter_horizontal (ModelAdmin attribute), 715 
filter_vertical (ModelAdmin attribute), 715 
form (ModelAdmin attribute), 715 
formfield_overrides (ModelAdmin attribute), 716 
inlines (ModelAdmin attribute), 716 
list_display (ModelAdmin attribute), 716 
list_display_links (ModelAdmin attribute), 721 
list_editable (ModelAdmin attribute), 721 
list_filter (ModelAdmin attribute), 721 
list_max_show_all (ModelAdmin attribute), 724 
list_per_page (ModelAdmin attribute), 724 
list_select_related (ModelAdmin attribute), 724 
ordering (ModelAdmin attribute), 724 
paginator (ModelAdmin attribute), 725 
object_history_template (ModelAdmin attribute), 729 
popup_response_template (ModelAdmin attribute), 729 
prepopulated_fields (ModelAdmin attribute), 725 
preserve_filters (ModelAdmin attribute), 725 
radio_fields (ModelAdmin attribute), 725 
raw_id_fields (ModelAdmin attribute), 726 
readonly_fields (ModelAdmin attribute), 726 
save_as (ModelAdmin attribute), 727 
save_as_continue (ModelAdmin attribute), 727 
save_on_top (ModelAdmin attribute), 727 
search_fields (ModelAdmin attribute), 727 
show_full_result_count (ModelAdmin attribute), 728 
sortable_by (ModelAdmin attribute), 728 
view_on_site (ModelAdmin attribute), 728 

add_view() (ModelAdmin method), 738 
change_view() (ModelAdmin method), 738 
changelist_view() (ModelAdmin method), 738 
delete_model() (ModelAdmin method), 730 
delete_queryset() (ModelAdmin method), 730 
delete_view() (ModelAdmin method), 738 
formfield_for_choice_field() (ModelAdmin method), 735 
formfield_for_foreignkey() (ModelAdmin method), 734 
formfield_for_manytomany() (ModelAdmin method), 734 
get_actions() (ModelAdmin method), 705 
get_autocomplete_fields() (ModelAdmin method), 731 
get_changeform_initial_data() (ModelAdmin method), 737 
get_changelist() (ModelAdmin method), 735 
get_changelist_form() (ModelAdmin method), 735 
get_changelist_formset() (ModelAdmin method), 736 
get_deleted_objects() (ModelAdmin method), 737 
get_exclude() (ModelAdmin method), 731 
get_fields() (ModelAdmin method), 732 
get_fieldsets() (ModelAdmin method), 732 
get_form() (ModelAdmin method), 734 
get_formsets_with_inlines() (ModelAdmin method), 734 
get_inline_instances() (ModelAdmin method), 732 
get_list_display() (ModelAdmin method), 731 
get_list_display_links() (ModelAdmin method), 731 
get_list_filter() (ModelAdmin method), 732 
get_list_select_related() (ModelAdmin method), 732 
get_ordering() (ModelAdmin method), 730 
get_paginator() (ModelAdmin method), 737 
get_prepopulated_fields() (ModelAdmin method), 731 
get_queryset() (ModelAdmin method), 736 
get_readonly_fields() (ModelAdmin method), 731 
get_search_fields() (ModelAdmin method), 732 
get_search_results() (ModelAdmin method), 730 
get_sortable_by() (ModelAdmin method), 732 
get_urls() (ModelAdmin method), 732 
has_add_permission() (ModelAdmin method), 736 
has_change_permission() (ModelAdmin method), 736 
has_delete_permission() (ModelAdmin method), 736 
has_module_permission() (ModelAdmin method), 736 
has_view_permission() (ModelAdmin method), 736 
history_view() (ModelAdmin method), 738 
lookup_allowed() (ModelAdmin method), 736 
message_user() (ModelAdmin method), 737 
response_add() (ModelAdmin method), 737 
response_change() (ModelAdmin method), 737 
response_delete() (ModelAdmin method), 737 
save_formset() (ModelAdmin method), 730 
save_model() (ModelAdmin method), 729 
save_related() (ModelAdmin method), 731 
```

InlineModelAdmin

```python
can_delete (InlineModelAdmin attribute), 742 
classes (InlineModelAdmin attribute), 741 
extra (InlineModelAdmin attribute), 741 
form (InlineModelAdmin attribute), 741 
formset (InlineModelAdmin attribute), 741 
fk_name (InlineModelAdmin attribute), 741 
max_num (InlineModelAdmin attribute), 741 
min_num (InlineModelAdmin attribute), 741 
model (InlineModelAdmin attribute), 741 
raw_id_fields (InlineModelAdmin attribute), 742 
show_change_link (InlineModelAdmin attribute), 742 
template (InlineModelAdmin attribute), 742 
verbose_name (InlineModelAdmin attribute), 742 
verbose_name_plural (InlineModelAdmin attribute), 742 

get_max_num() (InlineModelAdmin method), 742 
get_min_num() (InlineModelAdmin method), 743 

get_extra() (InlineModelAdmin method), 742 
get_formset() (InlineModelAdmin method), 742 

has_add_permission() (InlineModelAdmin method), 743 
has_change_permission() (InlineModelAdmin method), 743 
has_delete_permission() (InlineModelAdmin method), 743 
```

GenericInlineModelAdmin

```python
ct_field (GenericInlineModelAdmin attribute), 768 
ct_fk_field (GenericInlineModelAdmin attribute), 768 
```

LogEntry

```python
action_flag (LogEntry attribute), 753 
action_time (LogEntry attribute), 753 
change_message (LogEntry attribute), 753 
content_type (LogEntry attribute), 753 
object_id (LogEntry attribute), 753 
object_repr (LogEntry attribute), 753 
user (LogEntry attribute), 753 

get_change_message() (LogEntry method), 753 
get_edited_object() (LogEntry method), 753 
```

## Auth

<!--
get_permission_required() (PermissionRequiredMixin method), 376 
has_permission() (PermissionRequiredMixin method), 377 

clean() (models.AbstractUser method), 407 

auth() (in module django.contrib.auth.context_processors), 1379 

get_email_field_name() (django.contrib.auth.models.AbstractBaseUser class method), 406 
normalize_username() (django.contrib.auth.models.AbstractBaseUser class method), 406 

validators.ASCIIUsernameValidator (class in django.contrib.auth), 760 
validators.UnicodeUsernameValidator (class in django.contrib.auth), 760 

AccessMixin (class in django.contrib.auth.mixins), 377 
LoginRequiredMixin (class in django.contrib.auth.mixins), 374 
PermissionRequiredMixin (class in django.contrib.auth.mixins), 376 
UserPassesTestMixin (class in django.contrib.auth.mixins), 375 

Old
staff_member_required() (in module django.contrib.admin.views.decorators), 713 (redirect_field_name=’next’, login_url=’admin:login’)
-->

Contrib Auth

```python
authenticate() (in module django.contrib.auth), 368 
login() (in module django.contrib.auth), 371 
logout() (in module django.contrib.auth), 372 
get_user() (in module django.contrib.auth), 762 
get_user_model() (in module django.contrib.auth), 403 
is_active (in module django.contrib.auth), 409 
is_staff (in module django.contrib.auth), 409 

update_session_auth_hash() (in module django.contrib.auth), 378 
```

Auth Forms

```python
AuthenticationForm (class in django.contrib.auth.forms), 385 
PasswordChangeForm (class in django.contrib.auth.forms), 386 
PasswordResetForm (class in django.contrib.auth.forms), 386 
SetPasswordForm (class in django.contrib.auth.forms), 386 
```

Auth Forms- Admin

```python
UserCreationForm (class in django.contrib.auth.forms), 386 
UserChangeForm (class in django.contrib.auth.forms), 386 
AdminPasswordChangeForm (class in django.contrib.auth.forms), 385 
```

Auth Views

```python
LoginView (class in django.contrib.auth.views), 379 
LogoutView (class in django.contrib.auth.views), 381 

PasswordChangeView (class in django.contrib.auth.views), 382 
PasswordChangeDoneView (class in django.contrib.auth.views), 382 

PasswordResetView (class in django.contrib.auth.views), 382 
PasswordResetCompleteView (class in django.contrib.auth.views), 384 
PasswordResetConfirmView (class in django.contrib.auth.views), 384 
PasswordResetDoneView (class in django.contrib.auth.views), 383 

logout_then_login() (in module django.contrib.auth.views), 382 
redirect_to_login() (in module django.contrib.auth.views), 385 
```

User

```python
models.User (class in django.contrib.auth), 755–757 
```

User Attributes- Is Anonymous

```python
is_anonymous (models.User attribute), 756 
```

User Attributes- Personal Details

```python
first_name (models.User attribute), 755 
last_name (models.User attribute), 756 
email (models.User attribute), 756 
password (models.User attribute), 756 
```

User Attributes- Username and Permissions

```python
username (models.User attribute), 755 
user_permissions (models.User attribute), 756 
username_validator (models.User attribute), 757 
```

User Attributes- Is Authenticated

```python
is_authenticated (models.User attribute), 756 
```

User Attributes- Is Active, Last Login, Date Joined 

```python
is_active (models.User attribute), 756 
date_joined (models.User attribute), 756 
last_login (models.User attribute), 756 
```

User Attributes- Superuser, Staff, Group

```python
is_staff (models.User attribute), 756 
is_superuser (models.User attribute), 756 
groups (models.User attribute), 756 
```

User Methods- Get Name/Username

```python
get_short_name() (models.User method), 757 
get_full_name() (models.User method), 757 
get_username() (models.User method), 757 
```

User Methods- Email User

```python
email_user() (models.User method), 758 
```

User Methods- Passwords and Permissions

```python
get_all_permissions() (models.User method), 758 
check_password() (models.User method), 757 
get_group_permissions() (models.User method), 757 
has_module_perms() (models.User method), 758 
has_perm() (models.User method), 758 
has_perms() (models.User method), 758 
has_usable_password() (models.User method), 757 
set_password() (models.User method), 757 
set_unusable_password() (models.User method), 757 
```

User Manager

```python
models.UserManager (class in django.contrib.auth), 758 
```

```python
create_superuser() (models.UserManager method), 758 
create_user() (models.UserManager method), 758 
```

Anonymous User

```python
models.AnonymousUser (class in django.contrib.auth), 758 
```

```python
is_anonymous (models.User attribute), 756 
```

Abstract User

```python
models.AbstractUser (class in django.contrib.auth), 407 
```

Abstract Base User

```python
models.AbstractBaseUser (class in django.contrib.auth), 406 
```

```python
clean() (models.AbstractBaseUser method), 406 
check_password() (models.AbstractBaseUser method), 406 
get_session_auth_hash() (models.AbstractBaseUser method), 407 
get_username() (models.AbstractBaseUser method), 406 
has_usable_password() (models.AbstractBaseUser method), 407 
is_anonymous (models.AbstractBaseUser attribute), 406 
is_authenticated (models.AbstractBaseUser attribute), 406 
set_password() (models.AbstractBaseUser method), 406 
set_unusable_password() (models.AbstractBaseUser method), 406 
```

Base User Manager

```python
models.BaseUserManager (class in django.contrib.auth), 407 

normalize_email() (django.contrib.auth.models.BaseUserManager class method), 408 
```

```python
get_by_natural_key() (models.BaseUserManager method), 408 
make_random_password() (models.BaseUserManager method), 408 
```

Custom User

```python
models.CustomUser (class in django.contrib.auth), 405, 409 
```

```python
EMAIL_FIELD (models.CustomUser attribute), 405 
REQUIRED_FIELDS (models.CustomUser attribute), 405 
USERNAME_FIELD (models.CustomUser attribute), 405 
is_active (models.CustomUser attribute), 405 
get_full_name() (models.CustomUser method), 405 
get_short_name() (models.CustomUser method), 406 
```

Custom User Manager

```python
models.CustomUserManager (class in django.contrib.auth), 407 
```

```python
create_user() (models.CustomUserManager method), 407 
create_superuser() (models.CustomUserManager method), 407 
```

Auth Group

```python
models.Group (class in django.contrib.auth), 759 
```

```python
name (models.Group attribute), 759 
permissions (models.Group attribute), 760 
```

Auth Permission

```python
models.Permission (class in django.contrib.auth), 759 
```

```python
name (models.Permission attribute), 759 
content_type (models.Permission attribute), 759 
codename (models.Permission attribute), 759 
```

Auth Permission Mixins

```python
models.PermissionsMixin (class in django.contrib.auth), 409 
```

```python
get_all_permissions() (models.PermissionsMixin method), 409 
get_group_permissions() (models.PermissionsMixin method), 409 
has_module_perms() (models.PermissionsMixin method), 410 
has_perm() (models.PermissionsMixin method), 409 
has_perms() (models.PermissionsMixin method), 409 
is_superuser (models.PermissionsMixin attribute), 409 
```

Auth Decorators

```python
login_required() (in module django.contrib.auth.decorators), 372 
permission_required() (in module django.contrib.auth.decorators), 375 
user_passes_test() (in module django.contrib.auth.decorators), 374 
```

Auth Password Validation

```python
MinimumLengthValidator (class in django.contrib.auth.password_validation), 395 
CommonPasswordValidator (class in django.contrib.auth.password_validation), 396 
NumericPasswordValidator (class in django.contrib.auth.password_validation), 396 
UserAttributeSimilarityValidator (class in django.contrib.auth.password_validation), 395 
```

```python
get_password_validators() (in module django.contrib.auth.password_validation), 396 
password_changed() (in module django.contrib.auth.password_validation), 396 
password_validators_help_text_html() (in module django.contrib.auth.password_validation), 396 
password_validators_help_texts() (in module django.contrib.auth.password_validation), 396 
validate_password() (in module django.contrib.auth.password_validation), 396 
```

Auth Middleware

```python
AuthenticationMiddleware (class in django.contrib.auth.middleware), 1093 
PersistentRemoteUserMiddleware (class in django.contrib.auth.middleware), 1093 
RemoteUserMiddleware (class in django.contrib.auth.middleware), 1093 
```

Auth Hashers

```python
check_password() (in module django.contrib.auth.hashers), 394 
is_password_usable() (in module django.contrib.auth.hashers), 394 
make_password() (in module django.contrib.auth.hashers), 394 
```

Auth Signals

```python
user_logged_in() (in module django.contrib.auth.signals), 760 
user_logged_out() (in module django.contrib.auth.signals), 760 
user_login_failed() (in module django.contrib.auth.signals), 760 
```

```ModelBackend``` and ```RemoteUserBackend```

```python
AllowAllUsersModelBackend (class in django.contrib.auth.backends), 761 
AllowAllUsersRemoteUserBackend (class in django.contrib.auth.backends), 762 

ModelBackend (class in django.contrib.auth.backends), 761 
authenticate() (ModelBackend method), 761 
get_group_permissions() (ModelBackend method), 761 
get_all_permissions() (ModelBackend method), 761 
get_user_permissions() (ModelBackend method), 761 
has_module_perms() (ModelBackend method), 761 
has_perm() (ModelBackend method), 761 
user_can_authenticate() (ModelBackend method), 761 

RemoteUserBackend (class in django.contrib.auth.backends), 761 
authenticate() (RemoteUserBackend method), 762 
clean_username() (RemoteUserBackend method), 762 
configure_user() (RemoteUserBackend method), 762 
create_unknown_user (RemoteUserBackend attribute), 762 
user_can_authenticate() (RemoteUserBackend method), 762 
```

## Mixins

<!--
register_lookup() (django.db.models.lookups.RegisterLookupMixin class method), 1208 

django.views.generic.detail.SingleObjectMixin (built-in class), 669 
django.views.generic.detail.SingleObjectTemplateResponseMixin (built-in class), 670 
django.views.generic.list.MultipleObjectMixin (built-in class), 671 
django.views.generic.list.MultipleObjectTemplateResponseMixin (built-in class), 673 
django.views.generic.base.TemplateResponseMixin (built-in class), 668 
django.views.generic.base.ContextMixin (built-in class), 667 
django.views.generic.edit.DeletionMixin (built-in class), 676 
django.views.generic.edit.FormMixin (built-in class), 674 
django.views.generic.edit.ModelFormMixin (built-in class), 675 
-->

SingleObjectMixin

```python
context_object_name (django.views.generic.detail.SingleObjectMixin attribute), 669 
model (django.views.generic.detail.SingleObjectMixin attribute), 669 
pk_url_kwarg (django.views.generic.detail.SingleObjectMixin attribute), 669 
query_pk_and_slug (django.views.generic.detail.SingleObjectMixin attribute), 669 
queryset (django.views.generic.detail.SingleObjectMixin attribute), 669 
slug_field (django.views.generic.detail.SingleObjectMixin attribute), 669 
slug_url_kwarg (django.views.generic.detail.SingleObjectMixin attribute), 669 

get_context_data() (django.views.generic.detail.SingleObjectMixin method), 670 
get_context_object_name() (django.views.generic.detail.SingleObjectMixin method), 670 
get_object() (django.views.generic.detail.SingleObjectMixin method), 670 
get_queryset() (django.views.generic.detail.SingleObjectMixin method), 670 
get_slug_field() (django.views.generic.detail.SingleObjectMixin method), 670 
```

SingleObjectTemplateResponseMixin

```python
template_name_field (django.views.generic.detail.SingleObjectTemplateResponseMixin attribute), 671 
template_name_suffix (django.views.generic.detail.SingleObjectTemplateResponseMixin attribute), 671 

get_template_names() (django.views.generic.detail.SingleObjectTemplateResponseMixin method), 671 
```

MultipleObjectMixin

```python
allow_empty (django.views.generic.list.MultipleObjectMixin attribute), 672 
context_object_name (django.views.generic.list.MultipleObjectMixin attribute), 672 
model (django.views.generic.list.MultipleObjectMixin attribute), 672 
ordering (django.views.generic.list.MultipleObjectMixin attribute), 672 
page_kwarg (django.views.generic.list.MultipleObjectMixin attribute), 672 
paginate_by (django.views.generic.list.MultipleObjectMixin attribute), 672 
paginate_orphans (django.views.generic.list.MultipleObjectMixin attribute), 672 
paginator_class (django.views.generic.list.MultipleObjectMixin attribute), 672 
queryset (django.views.generic.list.MultipleObjectMixin attribute), 672 

get_allow_empty() (django.views.generic.list.MultipleObjectMixin method), 673 
get_context_data() (django.views.generic.list.MultipleObjectMixin method), 673 
get_context_object_name() (django.views.generic.list.MultipleObjectMixin method), 673 
get_ordering() (django.views.generic.list.MultipleObjectMixin method), 672 
get_paginate_by() (django.views.generic.list.MultipleObjectMixin method), 673 
get_paginate_orphans() (django.views.generic.list.MultipleObjectMixin method), 673 
get_paginator() (django.views.generic.list.MultipleObjectMixin method), 673 
get_queryset() (django.views.generic.list.MultipleObjectMixin method), 672 
paginate_queryset() (django.views.generic.list.MultipleObjectMixin method), 672 
```

MultipleObjectTemplateResponseMixin

```python
template_name_suffix (django.views.generic.list.MultipleObjectTemplateResponseMixin attribute), 673 

get_template_names() (django.views.generic.list.MultipleObjectTemplateResponseMixin method), 673 
```

TemplateResponseMixin

```python
content_type (django.views.generic.base.TemplateResponseMixin attribute), 668 
response_class (django.views.generic.base.TemplateResponseMixin attribute), 668 
template_engine (django.views.generic.base.TemplateResponseMixin attribute), 668 
template_name (django.views.generic.base.TemplateResponseMixin attribute), 668 

get_template_names() (django.views.generic.base.TemplateResponseMixin method), 669 
render_to_response() (django.views.generic.base.TemplateResponseMixin method), 669 
```

ContextMixin

```python
extra_context (django.views.generic.base.ContextMixin attribute), 667 

get_context_data() (django.views.generic.base.ContextMixin method), 668 
```

DeletionMixin

```python
success_url (django.views.generic.edit.DeletionMixin attribute), 676 

delete() (django.views.generic.edit.DeletionMixin method), 676 
get_success_url() (django.views.generic.edit.DeletionMixin method), 676 
```

FormMixin

```python
form_class (django.views.generic.edit.FormMixin attribute), 674 
initial (django.views.generic.edit.FormMixin attribute), 674 
prefix (django.views.generic.edit.FormMixin attribute), 674 
success_url (django.views.generic.edit.FormMixin attribute), 674 

form_invalid() (django.views.generic.edit.FormMixin method), 675 
form_valid() (django.views.generic.edit.FormMixin method), 675 
get_context_data() (django.views.generic.edit.FormMixin method), 675 
get_form() (django.views.generic.edit.FormMixin method), 674 
get_form_class() (django.views.generic.edit.FormMixin method), 674 
get_form_kwargs() (django.views.generic.edit.FormMixin method), 674 
get_initial() (django.views.generic.edit.FormMixin method), 674 
get_prefix() (django.views.generic.edit.FormMixin method), 674 
get_success_url() (django.views.generic.edit.FormMixin method), 675 
```

ModelFormMixin

```python
fields (django.views.generic.edit.ModelFormMixin attribute), 675 
model (django.views.generic.edit.ModelFormMixin attribute), 675 
success_url (django.views.generic.edit.ModelFormMixin attribute), 675 

form_invalid() (django.views.generic.edit.ModelFormMixin method), 676 
form_valid() (django.views.generic.edit.ModelFormMixin method), 676 
get_form_class() (django.views.generic.edit.ModelFormMixin method), 675 
get_form_kwargs() (django.views.generic.edit.ModelFormMixin method), 675 
get_success_url() (django.views.generic.edit.ModelFormMixin method), 675 
```

Mixin Attributes and Methods

```python
allow_future (DateMixin attribute), 679 
date_field (DateMixin attribute), 679 
get_allow_future() (DateMixin method), 680 
get_date_field() (DateMixin method), 680 

day (DayMixin attribute), 678 
day_format (DayMixin attribute), 678 
get_day() (DayMixin method), 678 
get_day_format() (DayMixin method), 678 
get_next_day() (DayMixin method), 678 
get_previous_day() (DayMixin method), 678 

get_next_week() (WeekMixin method), 679 
get_prev_week() (WeekMixin method), 679 
get_week() (WeekMixin method), 679 
get_week_format() (WeekMixin method), 679 
week (WeekMixin attribute), 679 
week_format (WeekMixin attribute), 679 

get_month() (MonthMixin method), 678 
get_month_format() (MonthMixin method), 677 
get_next_month() (MonthMixin method), 678 
get_previous_month() (MonthMixin method), 678 
month (MonthMixin attribute), 677 
month_format (MonthMixin attribute), 677 

get_next_year() (YearMixin method), 677 
get_previous_year() (YearMixin method), 677 
get_year() (YearMixin method), 677 
get_year_format() (YearMixin method), 677 
year (YearMixin attribute), 677 
year_format (YearMixin attribute), 677
```

## Django Field Look-Up Types- PostgreSQL Specific

JSON (PostgreSQL Specific)

```python
jsonfield.contained_by field lookup type, 910 
jsonfield.contains field lookup type, 910 
jsonfield.has_any_keys field lookup type, 910 
jsonfield.has_key field lookup type, 910 
jsonfield.has_keys field lookup type, 910 
jsonfield.key field lookup type, 909 
```

Array (PostgreSQL Specific)

```python
arrayfield.contained_by field lookup type, 903 
arrayfield.contains field lookup type, 903 
arrayfield.index field lookup type, 904 
arrayfield.len field lookup type, 904 
arrayfield.overlap field lookup type, 904 
arrayfield.slice field lookup type, 905 
```

Range (PostgreSQL Specific)

```python
rangefield.adjacent_to field lookup type, 913 
rangefield.contained_by field lookup type, 912 
rangefield.contains field lookup type, 912 
rangefield.endswith field lookup type, 914 
rangefield.fully_gt field lookup type, 913 
rangefield.fully_lt field lookup type, 913 
rangefield.isempty field lookup type, 914 
rangefield.not_gt field lookup type, 913 
rangefield.not_lt field lookup type, 913 
rangefield.overlap field lookup type, 912 
rangefield.startswith field lookup type, 914 
```

HStore (PostgreSQL Specific)

```python
hstorefield.contained_by field lookup type, 907 
hstorefield.contains field lookup type, 907 
hstorefield.has_any_keys field lookup type, 907 
hstorefield.has_key field lookup type, 907 
hstorefield.has_keys field lookup type, 908 
hstorefield.key field lookup type, 906 
hstorefield.keys field lookup type, 908 
hstorefield.values field lookup type, 908 
```

Trigram (PostgreSQL Specific) 

```python
trigram_similar field lookup type, 920 
```

Unaccent (PostgreSQL Specific)

```python
unaccent field lookup type, 920 
```
