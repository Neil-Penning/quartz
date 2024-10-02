---
id: Calendar
aliases: []
tags: []
---


# Goal:
I need a text based calendar.
# Example
Each event's data takes place on one line, with context from previously indented.

- `>` Start time
- `-` Duration
- `+`
- `#` Tag
    - `#{}` tags
- `@` Location
    - `@{}` Locations
- `%` With person
    - `%{}` With People
- `''` Name of Event
- `""` Description
- `*` Timezone
- `:` Continue on next line
```
// Day Notation
2024-09-20:
    > 1400 'Drop off Air Purifier' % [[Anna_Penning]]
    > 1800 'Drive to TN' + 3hr
2024-09-23: 
    > 0800 + 1hr 'Run'
    > 1500 - 1600 Read Paper %{[[Anna_Penning]],[[Annie_Skinner]],[[Teagan]]}
    > 1700 + 2hr @ CRAB #{climbing}
2024-08-04:


2024_38
    > Mon
        > 1500

```
