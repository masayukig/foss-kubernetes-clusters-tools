FOSSAsia Summit 2018
====================

.. figlet:: FOSS Kubernetes management tools

.. code:: yaml

   Name     : Masayuki Igawa (Twitter/GitHub/freenode: masayukig)
   Slide URL: https://github.com/masayukig/foss-kubernetes-clusters-tools
   Date     : 14:10-14:30, Sunday, March 25 2018

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

   * OpenStack Up/Down stream Programmer
     * Quarity Assurance (Tempest, stestr..)
   * Working at SUSE
   * Mesos User Group Tokyo


What is this talking about Kubernetes(k8s)?
===========================================

* Famous and interesting technology :)
* FOSS

  * As an entry point
* DIY (not GKE, EKS, AKS..)


My private cloud
================

* 3 x 1U server + 1 workstation

  * Powered by LackRack: https://wiki.eth0.nl/index.php/LackRack
  * https://github.com/mtreinish/dirty-clouds-done-dirt-cheap/tree/fossasia-2018
* OpenStack Queens on openSUSE Leap 42.3

  * Network: very flat, VMs are connected to a home router
  * `Very simple network`_ (see 'MyPrivateOpenStackCloud.png')

.. _Very simple network: https://goo.gl/P4UY71


What is Kubernetes?
===================

.. container:: progressive

   * Container Orchestration tool

     * Self-healing, Automatic binpacking, Horizontal scaling,
       autscaling, load blance, etc, etc..
   * Open Source

     * Apache-2.0 License
   * Difficult to deploy (if you want to use it in a **production** )


Why should we use FOSS tools? (why not GKE, etc?)
=================================================

.. container:: progressive

   * Free (not only money)
   * Source code
   * To know everything -> Fun :)

.. container:: handout

   If you want to just try to use k8s, using GKE is an very good
   option :) But if you'd like to know/understand the mechanism, it's
   good to build it by yourself.


FOSS k8s tools
==============

.. container:: progressive

   * minikube: https://github.com/kubernetes/minikube
   * OpenStack Magnum: https://docs.openstack.org/magnum/
   * Mesos DC/OS: http://mesos.apache.org/  https://dcos.io/
   * Rancher: https://rancher.com/
   * minikube: https://kubernetes.io/docs/getting-started-guides/minikube
   * etc..


OpenStack Magnum
================

.. container:: progressive

   * OpenStack Project: https://wiki.openstack.org/wiki/Magnum
   * API services for Container orchestration engines

     * Supported: Docker Swarm, Kubernetes, Apache Mesos


Mesos DC/OS
===========

.. container:: progressive

   * Mesos: Apache project

| Apache Mesos abstracts CPU, memory, storage, and other compute
| resources away from machines (physical or virtual), enabling
| fault-tolerant and elastic distributed systems to easily be built
| and run effectively.

.. container:: progressive

   * DC/OS: Apache 2.0
   * Fancy catalog

| DC/OS (the datacenter operating system) is an open-source,
| distributed operating system based on the Apache Mesos distributed
| systems kernel.

.. container:: progressive

   * http://mesos.apache.org/
     https://dcos.io/


Rancher
=======

.. container:: progressive

   * License: Apache 2.0

| Complete container management platform
| Deploy and manage Kubernetes with ease

.. container:: progressive

   * Very easy to setup as a first step
   * Fancy catalog


Pros/Cons
=========

.. container:: progressive

   * OpenStack Magnum

     * Building OpenStack env is not easy
     * https://docs.openstack.org/magnum/
   * Mesos DC/OS

     * Need several nodes at least
   * Rancher

     * Start from 1 node
     * k8s CLI (shell)


Future work & Conclusion
========================

* Real usecase

  * IoT
  * As test environments
* More stable infrastructure (SUSE Enterprise Linux?)
* Make my OpenStack cloud in a private network
* Use OpenStack Magnum project

* We can play k8s with FOSS tools easier(?)
* Having a private cloud(s) is very fun!


Demo(OpenStack Magnum, Mesos DC/OS, Rancher...)
===============================================

* http://rancher.com/docs/rancher/latest/en/quick-start-guide/


