## adding sponsors


- we list sponsors by sponsor_group.name (think of this as "sponsorship level")
from data/homepage.yml
- sponsor groups are in the order they appear in data/homepage.yml
- sponsor_item values are rendered in the order they appear in data/homepage.yml
- create sponsor md page file in content/sponsors. filename can be anything, but
as it will be an URL, please consider ascii chars only, no whitespaces please :)
- please pay attention that the specific `name` value in data.homepage for the
sponsor is the same as md metadata section `title` value. If a match is not found
the sponsor will not be listed in the generated page.
- sponsor page type should be set to `sponsor` and layout `single` (see .template.md)
