Dashboard implementation example
==============================================

**This page is being updated. Will be finished soon.**

Here's an example of a Dashoboard set up:

.. image:: admin-dashboard-usage.png

Under Usage, information about active readers and active contributors are shown. What should be considered an active reader or an active contributor is defined in the Metrics settings, see: :doc:`Metric Settings </admin-settings/tenant-settings/settings/metrics/index>`

Under Page Status, something like the following is shown:

.. image:: admin-dashboard-page-status-new.png

What you see in the example is the total status for the tenant. You can choose to see status for just one of the publishing apps and/or just one of the page types.

For Underused Content, something like the following can be shown:

.. image:: admin-dashboard-underused-content.png

What should be considered underused content is defined in the Metrics settings, see link above.

Regarding Reach: How well we reach our target audience based on what we expect. The metric can be configured to a specific scope of pages and have a target number of users.

.. image:: admin-dashboard-reach.png

For Teamwork, you can see the number of active teamworks and if any has been created this week or this month:

.. image:: admin-dashboard-teamwork.png

Finally, for Communities, the following information is shown:

.. image:: admin-dashboard-communities-new.png

How it's done
-----------------
The layout in this implementation example is a tab section with six tabs:

.. image:: dashboard-example-tab-section.png

The settings for the tabs are similar. Here's the first tab as an example:

.. image:: dashboard-example-tab-settings.png

For Style, "Show Active Slider" is selected so it's clear which the active tab is:

.. image:: dashboard-example-tab-settings-style.png

On each tab a Metrics block is placed, with the following settings:

**Usage**: For this tab the Scope is set to "User Activity",  with the following Metrics:

.. image:: dashboard-example-tab-usage.png

**Page Status**: Here the setting for Scope is "Pages" with the following Metrics:

.. image:: dashboard-example-tab-page-status-new.png

**Underused Content**: The Scope for this tab is also set to page, but this time with the following Metrics:

.. image:: dashboard-example-tab-page-underused.png

**Reach**: On the Reach tab, two Metrics blocks are added.

For the "Corporate News Reach", the Scope is set this way:

.. image:: dashboard-example-tab-page-reach-news-new.png

And the Metrics, this way:

.. image:: dashboard-example-tab-page-reach-news-metrics-new.png

For the "Local News Reach", the Scope is set this way:

.. image:: dashboard-example-tab-page-reach-news-local-new.png

And the Metrics, this way:

.. image:: dashboard-example-tab-page-reach-news-local-metrics.png

**Teamwork**: For this tab, the Scope is set to "Teamwork", with three Metrics:

.. image:: dashboard-example-tab-teamwork-new.png

A filter is also added so you can choose the type of teamwork, based on template:

.. image:: dashboard-example-tab-teamwork-filter.png

**Communities**: For the "Communites tab" Scope is set to Pages, and the Page Type "Discussion":

.. image:: dashboard-example-tab-communities-scope.png

And with the following Metrics:

.. image:: dashboard-example-tab-communities-metrics-new.png

