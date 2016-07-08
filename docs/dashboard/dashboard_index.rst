.. _my-dashboard:

Dashboard
============

**Purpose:** The Dashboard provides users quick access to their projects and allows them to create new projects. 

At the top of the page, on the right side, is a green "Create new project" button. Clicking it allows a user to create a new project. A modal appears,::

	Title: (text field) [Select all] [Remove all]
	Affiliation
	(caret)More:
	Description: (text field)
	Template (optional)
	[Cancel][Create]

Users must type something in the Title field but may leave the others blank. Clicking Cancel returns the user to the dashboard with no changes. Clicking Create creates the new project and displays a modal::

	New project created successfully!
	[Keep working here][Go to new project]

Clicking Keep working here returns the user to the dashboard. Clicking "Go to new project" sends the user to the Project Overview page of his/her new project.

Below this green button is a text field, "Quick search your projects." Below the text box is a table displaying the 10 most recently updated Projects and Components on which the user is a contributor. Typing in the box filters the listings below according to what is typed. Users may type project/component names or Contributor names to filter. Below this text box is text, Go to My Projects (which links to the Project Organizer) or search (links to osf.io/search) the OSF.  

The table of recently updated projects and components contains 3 columns: Title, Contributors, Modified. Title includes the project title, affiliation, and component name, each separated with a "/". The lattermost of these three features appears in bold.

The user can sort by date last modified (ascending or descending) and Project or Component title (ascending or descending) by clicking the up or down arrows in the table heading. By default, the most recent 10 projects or components are shown. The user can click the down arrow below these 10 to produce more listings in groups of 10. 

Below the list of the user's projects are icons for OSF for Institutions affiliated partners. These appear 5 at a time on a carousel shifted with "<" and ">" markers. Clicking on an institution icon brings the user to the affiliated institution's landing page, where all public projects affiliated with that institution are listed. 

Below OSF for Institutions icons is a section called "Discover Public Projects." In this section, there are two columns: "New and Noteworthy" and "Most Popular." Each contains links to 5 public projects on the OSF. Below this is a button, "Search for more projects," which takes the user to https://osf.io/search/.

Below this section is a marketing section. Currently this displays information about OSF for Meetings, but it can be used to highlight other products or initiatives. 

The dashboard is accessed through the “My Dashboard” link in the :ref:`navigation bar <navigation-bar>` at the
top of the page; the url is simply https://osf.io, though it can also be reached via https://osf.io/dashboard.

When logging into the OSF, the "My Dashboard" is the default landing page.

.. _organizer:

Project Organizer
******************

.. include:: organizer.rst

.. _quick-tasks:

Quick Tasks
**************

.. include:: quick_tasks.rst

.. _watchlist:

Watchlist
************

.. include:: watchlist.rst
