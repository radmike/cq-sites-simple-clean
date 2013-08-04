Simple Clean Site
=================

Simple, basic CQ site structure based off of the CQ Blueprints Archetype

Contains only the CQ Blueprints Dependencies as a simple package that can be imported into CQ

This provides access to various custom CQ Blueprint Taglibs and OSGI bundles that can be leveraged across multiple CQ Projects, and deployed to a common repository.



Project Details
------------------

Details about the Simple Site's subprojects are included here.

### config Sub-Project

The config sub-project contains basic run-mode placeholders for per-environment configuration. Example runmode cover author/publish on local/CI/QA/PROD deployment targets

Config also supplies the standard install directory for auto-deployment of OSGI bundles via the included scripts and maven builders.

Finally, example ```/etc/map/...``` placeholder examples are included.

### view Sub-Project

The view sub-project contains the basic ```/etc/designs/simple-clean/...``` js/css/etc., as well as basic ```/apps/simple-clean/...``` pages, components, templates, and modules

### content Sub-Project

The content sub-project contains example pages and DAM assets to for the example pages

### services Sub-Project

The services sub-project is a placeholder for site-specific integrations. New sites should first develop code specific to the site, but can be factored out to more specific OSGI bundles at a future date.

### taglib Sub-Project

The taglib sub-project contains a placeholder for creating site-specific taglibs. These should help created cleaner JSP pages and components, automating repetitive JSP code actions or accessing Service-code in the related OSGI bundle.



About this Project
------------------

Taglibs require the CQ Dependencies to be deployed into the CQ repository. See the [CQ Dependencies](https://github.com/radmike/cq-dependencies) project for more information.

Based on the CQ Blueprints Maven Archetype:
http://www.cqblueprints.com/xwiki/bin/view/Blue+Prints/The+CQ+Project+Maven+Archetype

Generated from the com.cqblueprints.archetypes:multi-module Maven Archetype.



Building this Project
---------------------

This project is intended to work with Adobe CQ 5.5 and above.

The project includes various scripts useful for local and CI development. See the [CQ Scripts](https://github.com/radmike/cq-scripts) project for details on their functionality and usage.

To build this project manually you will need access to the Adobe Maven Repository and also the CQ Blueprints Maven Repository.

Check the following URLs for information on connecting to these two Repositories:

* Connecting to the CQ Blueprints Maven Repository - http://www.cqblueprints.com/xwiki/bin/view/Blue+Prints/Connecting+to+the+CQ+Blueprints+Repository
* Connecting to the Adobe Maven Repository - http://www.cqblueprints.com/xwiki/bin/view/Blue+Prints/Connecting+to+the+Adobe+Maven+Repository
