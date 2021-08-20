[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/integrated-business-planning-excel-add-in-templates)](https://api.reuse.software/info/github.com/SAP-samples/integrated-business-planning-excel-add-in-templates)

# Planning View Templates for the IBP Add-In for Microsoft Excel
Collection of best practices planning view templates for the SAP Integrated Business Planning (IBP) Add-In for Microsoft Excel.

## Overview
Template development is an important task during an S&OP / IBP implementation. Useful and easy-to use templates will contribute significantly to end user adoption and implementation project success. This repository contains a collection of best practices planning view templates for the SAP IBP Add-In for Microsoft Excel.
For more general information have a look at [SAP note 1790530](https://launchpad.support.sap.com/#/notes/1790530).

![screenshot of VBA Template](https://github.com/SAP-samples/integrated-business-planning-excel-add-in-templates/blob/main/media/screenshot.png "screenshot of a VBA Template")

## Download and Installation
Download best practice planning view templates that fits your need [here](https://github.com/SAP/integrated-business-planning-excel-add-in-templates/archive/master.zip).

For more information have a look at [SAP note 1790530](https://launchpad.support.sap.com/#/notes/1790530).

A prerequisite for the planning view templates is the IBP Add-In for Microsoft Excel. 

For more information about installing the IBP Add-In for Microsoft Excel have a look at [SAP note 2135948](https://launchpad.support.sap.com/#/notes/2135948).

After downloading the sample files, the Excel templates may not load properly, if their location isn’t set to be part of the Trusted Locations. You can add a Trusted Location in Excel by going to File > Options > Trust Center > Trust Center Settings … Trusted Locations > Add new location… > Browse.

## Limitations
* Chart in the formula based template only looks at 300 rows and they only work in English.
* The best practices templates are designed just for the SAP IBP Add-In for Microsoft Excel.

## Known Issues

- **copy/move sheet:**
    Users might want to copy sheets containing planning views using the native Excel copy/move function. For planning view sheets the native Excel copy/move is not supported: The IBP Add-In for Microsoft Excel will not recognize the sheet and omit it in the Edit View dialog. However, the template admin can copy the empty template sheets from the empty templates attached here - before they are filled with a planning view - and then proceed as with the first sheet with New View > Without Template on Current Sheet.

For more restrictions or known issues have a look at [SAP note 1790530](https://launchpad.support.sap.com/#/notes/1790530).

## How to obtain support
The best practices planning view templates are provided "as-is", no support is provided.

The best practices templates are not meant for production use. They are meant as an inspiration and as a stepping stone to get you started.

For additional support, [ask a question in SAP Community](https://answers.sap.com/questions/ask.html).

## License
Copyright (c) 2018 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
