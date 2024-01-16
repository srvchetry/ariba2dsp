# Getting Started

This repo is about using the underlying HANA Cloud of SAP Datasphere for integrating with SAP Ariba.

It contains these folders and files, following our recommended project layout:

# Configuration
Open Terminal in Business Application Studio and run npm i

# Build
Open Terminal and run cds build

# Deploy for local testing

Open Terminal and run cds deploy, followed by cds watch --profile hybrid

# Deploy as an application in BTP

Open Terminal and create a .mtar file by running mbt build.
Right click on the mtar file and choose "Deploy MTA Archive" alternatively run command cf deploy <path-to-mtar-file>
