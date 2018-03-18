FOSSAsia Summit 2018
====================

.. figlet:: Comparison of FOSS k8s clusters management/deployment tools

.. code:: yaml

     Name     : Masayuki Igawa
     Slide URL: https://github.com/masayukig/terminal-software-again
     Date     : Sunday, March 25 2018

.. Kubernetes(k8s) is the most popular and famous container orchestration
   software these days. And we can use it through Kubernetes as a
   Services such as GKE, EKS, etc on public clouds. However, I love FOSS!
   So, I'd like to use it on my machine (I call this my "private" cloud)
   as possible :) Fortunately, there are so many k8s FOSS cluster
   management/deployment tools recently such as OpenStack Magnum, Mesos
   DC/OS, Rancher, etc.. We can use them as alternatives.

   In this talk, attendees will get to know "what is Kubernetes?", "how
   do we deploy it?", "What's the difference between the k8s FOSS
   management tools?" and their pros and cons.

DISCLAIMER
==========

| These slide are my own opinion.


Who am I?
=========

.. container:: progressive

   * OpenStack Programmer
   * SUSE
   * Linux User
   * Mesos User Group Tokyo


What is Kubernetes?
===================

.. container:: progressive

   * Container Orchestration tool
   * Open Source
   * Difficult to deploy


Why should we use FOSS tools?
=============================

.. container:: progressive

   * Free
   * Source code
   * Fun

FOSS k8s tools
==============

.. container:: progressive

   * OpenStack Magnum
   * Mesos DC/OS
   * Rancher

Pros/Cons
=========

.. container:: progressive

   * OpenStack Magnum
     * Building OpenStack env is not easy
   * Mesos DC/OS
     * Need several nodes at least
   * Rancher
     * Start from 1 node
     * k8s CLI (shell)


Demo(OpenStack Magnum, Mesos DC/OS, Rancher...)
===============================================

* http://rancher.com/docs/rancher/latest/en/quick-start-guide/


