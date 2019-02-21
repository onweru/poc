## Add New Pages
You can add new pages inside the **_docs** directory. Always start your markdown file with the metadata (front matter)

```yaml 
---
layout: page
permalink: /working-with-communities-in-epidemics/
categories:
  - Africa
  - Asia
  - Violence
---
```

## Choose Categories to Highlight
Edit the **_data/highlights.yml**. These will show on home page

## Add Images
Store your images inside **assets/images** directory. To include the image in  your markdown file link it as follows:

```markdown
![alt description](/assets/images/finame.extension)
```