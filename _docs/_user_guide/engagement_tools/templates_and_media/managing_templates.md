---
nav_title: Managing Templates
article_title: Managing Templates
page_order: 3

page_type: reference
description: "This reference article describes how to duplicate and archive templates in the Templates & Media section of the Braze dashboard."
tool:
  - Templates
  - Media

---

# Managing templates

> Archiving or duplicating templates can help better organize and manage them. This reference article covers how to archive and duplicate templates in the **Templates** section of the Braze dashboard.

## Duplicate templates

### Duplicate an individual template

![][8]{: style="float:right;max-width:15%;margin-left:15px;"}

To duplicate an individual template, click the <i class="fas fa-cog"></i> cog icon for the individual template and select **Duplicate** from the dropdown menu.
<br><br>

{% alert note %}
For [Content Block]({{site.baseurl}}/user_guide/engagement_tools/templates_and_media/content_blocks/) templates, a draft copy is created. For all other templates a new duplicate copy is automatically created.
{% endalert %}

### Duplicate multiple templates

{% raw %}

Duplicating multiple templates can be achieved by selecting the checkbox next to the template name. First, select the templates and then click the **Duplicate** button that appears.

Duplicated templates can be found by sorting the **Last Edited** column. By default, new templates will by named `Copy of {{original template name}}`.

{% endraw %}

![GIF that shows a user selecting two templates and clicking "Duplicate", which results in a total of four templates, sorted by the time the templates were last edited.][9]

## Archive templates

{% alert note %}
If you are using the [older navigation]({{site.baseurl}}/navigation), **Templates** is **Templates & Media**.
{% endalert %}

### Archive an individual template

![Expanded settings dropdown menu that shows three options: Edit, Archive, and Duplicate, where the Archive option highlighted.][10]{: style="float:right;max-width:20%;margin-left:15px;"}

To archive an individual template, click the settings icon on the template grid screen and select **Archive**.

### Archive multiple templates

To archive multiple templates, select the checkbox next to each template that you want to archive. After you've selected multiple templates, click **Archive Selected**. You can find your archived templates by selecting **Archived** under **Show** in the template grid.

![Saved Drop & Drop Email Templates section that shows two selected templates: "Try Premium Template" and "Welcome Template". The "Archive Selected" button is highlighted by the user.][11]

{% alert important %}
Archiving is not currently available for [Link Templates]({{site.baseurl}}/user_guide/message_building_by_channel/email/link_templates/#link-templates).
{% endalert %}

[10]: {% image_buster /assets/img/template_archive_cog.png %}
[11]: {% image_buster /assets/img/archive_multiple_template.png %}
[8]: {% image_buster /assets/img/template_duplicate_cog.png %}
[9]: {% image_buster /assets/img/duplicate_multiple_template.gif %}