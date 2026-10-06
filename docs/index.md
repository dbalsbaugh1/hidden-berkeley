---
layout: default
title: Hidden Berkeley
---

# A Beginner's Berkeley
The best guide for the first couple months in Berkeley as a new resident. Reccomendation's of where to go and what to do for incoming student's success, included are the building's and their official souces.


<!-- Edit the heading and introduction above. The supplied loop below displays each row of the CSV. -->
{% for resource in site.data.locations %}

### {{ resource.name | escape }}

**Category:** {{ resource.category | escape }}  
**Area:** {{ resource.area | escape }}  
**Access note:** {{ resource.access_note | escape }}  
<a href="{{ resource.source_url | escape }}">Official source</a>

{% endfor %}

---

The entries come from this project's CSV. Confirm current details using the official links.
