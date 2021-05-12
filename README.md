# Design history for NHSBSA services

Forked from the exceptional work done on the [GOV.UK design history] (https://github.com/DFE-Digital/govuk-design-history)

We've added the NHS.UK branded toolkit.

A place for you to document your NHSBSA service designs.

<https://nhsbsa-design-history.netlify.app/>

## Purpose of this project

This repository makes it easy to:

* screenshot your designs
* create pages of screenshots to document designs
* document designs using the [GOV.UK Design System](https://design-system.service.gov.uk/)
* print pages of designs
* make designs shareable and linkable

## Installation

We use Eleventy v0.12.1 which requires Node 10 or newer.

* Clone this repository to a folder on your computer
* Open Terminal
* In Terminal, change the path to the repository
* Type `npm install` to install the dependencies

## Working locally

Most of the time you'll be adding new posts. If you're just doing this then:

* Open Terminal
* Type `npm start`

This will automatically restart the application with any changes to your posts an any images applied.

If you want to make changes to CSS and JavaScript, and watch for those changes, run `npm run dev`.

## Example design histories

* [Becoming a teacher design history](https://bat-design-history.netlify.app)
* [Increasing children’s internet access](https://increasing-access-history.herokuapp.com/)
* [WIP: Buy an NHS Prescription Prepayment Certificate design history
] (https://ppc-design-history.netlify.app/)

## Technical notes

The design history uses the [NHS.UK](https://service-manual.nhs.uk/) and the [Eleventy](https://www.11ty.dev) static site generator.
