---
title: Front Matter
permalink: /aspace/front-matter
layout: default
parent: ArchivesSpace
nav_order: 20
has_children: false
---
# Front Matter
{: .no_toc }
This section explains how to fill out the fields of the finding aid front matter in the collection's resource record. 

## Table of Contents
{: .no_toc .text-delta }

- TOC
{:toc}

# Resource Dates
For collections, provide dates according to [DACS 2.4](https://github.com/saa-ts-dacs/dacs/blob/master/06_part_I/03_chapter_02/04_date.md). If the use of a bulk date is appropriate for the collection, provide the bulk date in a separate date sub-form with the _Type_ of _bulk_.\

For more information on the fields in the Dates subform, see [Archival Object Dates](../aspace/archival-object-description.md#dates) section of this guide.

# Using the Date Calculator
ArchivesSpaces provides a date calculator, which will automatically find the earliest and latest dates in a collection and create a Date record for them. The Date Calculator will find the dates of each component under the current record, compare to find the earliest and latest dates, and generate a Date record using the range provided. Note that the Date Calculator will not provide information on bulk dates - it will only provide the total span for the record.The Date Calculator can be accessed under the _More_ menu from the Resource and Archival Object screen.

![date calculator](../aspace/Images/60-date-calculator.png)

Selecting _Calculate Dates_ will open the Date Calculator, which will ask for which type of date to find. Since all dates in a collection are set to _Creation_ by default, this can be left as-is. Select _Calculate Date Record_ to begin finding the date spans.

![date calculator](../aspace/Images/61-date-calculator.png)

Doing so will begin the date calculation process. For larger collections, this may take some time. Once the calculator has finished, it will provide a Date form with the calculated date span provided.

Selecting Create Date Record will save the Date form to the Resource/Archival Object that the Calculator was opened from. If you edit the finding aid after calculating the dates, you will need to re-calculate the dates to include the edits. The form does not automatically update.

![date form](../aspace/Images/62-date-form.jpg)


