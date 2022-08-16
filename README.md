# Sharepoint crash course

## Install

- install sharepoint: https://www.microsoft.com/fr-fr/microsoft-365/enterprise/office-365-e5?activetab=pivot%3aoverviewtab
- create an admin account

- After installing, go to office.com to access all apps and click sharepoint. Then click `Create Site` and choose `Team Site`

## Features

In sharepoint, you can create multiple elements by clicking on `New`:

### Document Library

Similar to one drive:

- each uploaded document has metadata
  - who uploaded it, who modified it last, etc.
  - We can also add other columns which allows to do search on them later on.
  - We can edit in grid view for fast editing
  - We can make some columns required
- versioning: can access previous versions of the file
  - by default, file not locked when editing so everybody can modify it at once
  - to block others from editing, we can `check out` the file. When it is finished we can `check in`. It allows us to see a comment that is shown in the version history

### Pages, News Post

Sharepoint allows to create web pages with a page builder. This can be used like a confluence page to give instructions for ex.
Sharepoint also allows news post
Lots of possibilities, similar to wordpress / elementor

### Sharepoint Lists

sharepoint way to contain database informations but very user friendly and extensible (each record can contain attachments for ex)

- When creating a list from excel, it must be formatted as table first

- Adding records

  - manually
  - copy from excel file: select the columns before paste

- Possibility to calculate column based on another
- Possibility to add form and column validation -> seems to work correctly by going to the old version when clicking on gear icon
- Possibility to add conditional formatting, either on column only or propagate to full row
- Possibility to add alerts to receive mails on changes
