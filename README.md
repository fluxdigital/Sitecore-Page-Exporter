# Sitecore-Page-Exporter
Sitecore Page Exporter Module for SPE - Export a page as a package and optionally the Sub-Pages, Datasources and Images.
The idea of the module is to use it to download pages from Production or other higher environments down to lower environments for debugging and testing.

## Pre-requisistes
You must have Sitecore Powershell Extensions intalled. This release has been tested with Sitecore 10.3 and SPE 6.4 but should work with older versions also.

## Install Notes
- Download the package from the release link below
- Install the package using the Sitecore package install option in the Sitecore Desktop
- You should now have Sitecore Page Exporter installed under the SPE module

## Usage

- To export an page right-click the page in the Content Editor and choose: Scripts > Export Page as Package:
  <img src="https://github.com/fluxdigital/Sitecore-Page-Exporter/blob/main/page-export-context-menu.png" width="500" align="left">
<br clear="both"/>
- The following options are then available to you:
  <img src="https://github.com/fluxdigital/Sitecore-Page-Exporter/blob/main/page-export-options.png" width="400" align="left">
<br clear="both"/>

- Choose your options and Click 'OK'
- Download and save the package
  <img src="https://github.com/fluxdigital/Sitecore-Page-Exporter/blob/main/page-export-download.png" width="500" align="left">
- You get an overview of the export if 
  <img src="https://github.com/fluxdigital/Sitecore-Page-Exporter/blob/main/page-exporter-summary.png" width="500" align="left">
- Upload the page to where you want to use it 

## Releases
[Download Release v1](https://github.com/fluxdigital/Sitecore-Page-Exporter/releases/tag/1.0.0)

