########
Overview
########

What is Arches?
===============

Arches is a web-based, geospatial information system for cultural heritage inventory and management. The platform is purpose-built for the international cultural heritage field, and it is designed to record all types of immovable heritage, including archaeological sites, buildings and other historic structures, landscapes, and heritage ensembles or districts.

Arches allows administrators to create their own database schema, and manage their own thesauri, while end users can search, explore and download the resources directly. In this way Arches is not only a robust and easy to use inventory system, it is also a perfect way to publish and disseminate your organization's cultural heritage information.

Arches is a web framework built on Django and is designed to make it easier to build applications that need:

    * **Geospatial data management** and geoprocessing like a GIS (Geograhic Information System) offers, but with a much more flexible approach for modeling the geometries associated with a resource.
    * the ability to **import arbitrary data schema** in the form of graphs as a means of defining the set of attributes that describe data resources
    * an **Ontology** as a means of formally naming and defining data types, properties, and the relationships between the data entities that describe a resource.
    * **Thesauri** to manage the controlled vocabularies needed to describe and index information in a consistent and uniform way.

Arches manages data "resources". Resources can represent almost anything you want: physical things (such as a cultural heritage object), temporal things (such as activities or events), actors (such as a person or organization), or conceptual objects (such as an image. document, or other information carrier).

Resources are defined as directed graphs (nodes connected by edges). Nodes in the graph are used to represent the attributes (or collection of attributes) of a resource and edges define the type of relationship between attributes. In practice, a resource graph in Arches functions much like a schema does in a relational database.

Arches provides core services for creating, reading, updating, and deleting resources. Because resources are defined as graphs, Arches provides the services needed to import and parse resource graphs, as well the ability to create and interact with instance graphs (e.g. an instance of a resource graph).

To promote consistent data creation, update, and indexing workflows, Arches implements a Reference Data Manager (RDM) that can manage thesauri. The RDM allows users with the appropriate privileges to update thesaurus entries in a manner compliant with SKOS (http://www.w3.org/2004/02/skos/) and assign the concepts within a thesaurus with data entry forms.

**Arches User and Developer forum:** https://community.archesproject.org/

Version History and Roadmap
---------------------------
The Arches project uses `semantic versioning <https://en.wikipedia.org/wiki/Software_versioning>`_ to describe unique states of the software. Arches was initially released in October 2013 as version 1.0. Since then, Arches has had 7 major releases and many more minor releases and patch releases (see :ref:`Arches Release Process`). For more details about the capabilities introduced in past versions and capabilities planned for future versions, please review: https://www.archesproject.org/roadmap/

.. important::

    **License:**
    Arches is free software and is licensed under the terms of the GNU Affero General Public License (http://www.gnu.org/licenses/agpl-3.0.html).

Who is Arches for?
==================

Arches is primarily intended for software developers who need to build flexible web applications and wish to hide the complexities of ontologies, thesauri, and geospatial data management from their users.

Documentation Overview
======================

This is the official documentation for Arches. It should provide you with background information on Arches, how to install it, and a good overview of its capabilities. While you are using Arches, be aware that much of the content here is also available by clicking the "?" symbol in the top-right corner of any page.

**Improve Our Documentation!** If you find errors, have suggestions, or want to make a contribution, these docs are managed in the `archesproject/arches-docs <https://github.com/archesproject/arches-docs>`_ repo.

Contributing To Arches
======================

Arches is open source software, which means that with your help it will continue to evolve and improve.

+ **Bug Reports and Code Contribution** If you find issues with the Arches interface or code, or have the means to contribute code to fix existing issues, please begin by reading our guidelines for `Contributing to Arches <https://github.com/archesproject/arches/blob/master/CONTRIBUTING.md>`_.
+ **Translations** We are always hoping to bring Arches to new audiences around the world. Please post on the `Arches Forum <https://community.archesproject.org/>`_ if you are interested in contributing a translation.
