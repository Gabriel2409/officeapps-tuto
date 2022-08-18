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

# Power Automate crash course

Powerautomate comes with office 365E5 so it should be installed already

## What it is

Microsoft solution to automate any task:

- Tasks can be simple or complex
- Tasks can use any application
- Tasks can have interactions from people

## Flows

### Introduction

Flows are available when clicking on My flows
There are also a lot of already built templates that can serve as inspiration

A flow is a visual representation of any task composed of a trigger and one or several actions.

Flows can be fairly complex (loops, conditions, approvals)

### Type of flows

There are 5 main type of flows

Is the flow complex? Is the data a default table in Microsoft dataverserse ?

- If yes: **Business process flow** (very specific usecase)
- If no, What actions should be automated?
  - If Power Automate Connectors (includes Http requests), Desktop, Web (RPA): **Desktop flow** (if an application does not have a connector I have to use a desktop flow. If it has one, i have the choice)
  - Else, Power Automate Connectors. How to trigger the flow?
    - Event: **Automated cloud flow**
    - Click: **instant cloud flow**
    - Time: **Scheduled cloud flow**

## Notes

- in flows, booleans evaluate to true or false without uppercase
- approvals evaluate to Approve or Reject. It can be completed with teams by choosing the approvals app or by mail

# Powerapps crash course

Powerapps comes with office 365E5 so it should be installed already

## What it is

Suite of apps, services, connectors and data platform that provides a rapid application development
environment to build custom apps.

Note that it is data platform agnostic so we can use a different data platform

## Features

- Easy to use
- can be run everywhere
- can be connected to anything
- can be customized

## Notes

- Actions start with On
- set variables with `Set(var_name, var_value)`. List of variables can be seen in variables ribbon
- functions : https://docs.microsoft.com/en-us/power-platform/power-fx/formula-reference
- galleries and forms: when submitting the form, powerapps can modify the underlying data source
