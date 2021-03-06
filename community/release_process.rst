Release Process
===============

Oro Product Versions
--------------------

Oro products are following `Semantic Versioning`_ strategy (MAJOR.MINOR.PATCH) with a few additions:

- **Major** version releases are reserved for backward incompatible architecture and technology changes, e.g. introduction of application namespaces, or switch to new version of Symfony
- **Minor** releases include new features and clear migration path in case of small backward incompatible updates
- **Patch** version releases are used for bug fixes and minor improvements


Release and Support Cycle
-------------------------

Oro Team is working on multiple products and releases them on time-based schedule, with new minor or major version coming out roughly every 2 months.

- **Regular** major or minor versions are released roughly every 2 months. These versions contain new features and capabilities that might not be complete yet, but still offer value to the users
- **Long-term support (LTS)** versions are released roughly every 6 months. These versions contain all completed features that were introduced in two previous regular versions

.. note::
    **Patch** versions are released roughly once in 2 weeks for all currently maintained regular and maintained/supported LTS versions.

The key difference between regular and LTS version is the duration of maintenance (bugfix) period. LTS versions are also supported for security fixes. 

- **Regular** versions are maintained for the next two release cycles, or roughly 4 months.
- **LTS** versions are maintained for 18 months after the release, and security fixes will be released for 18 more months

Below is the approximate schedule of Oro product releases and support timelines until 2019. Please take into account that numbering of major and minor versions is based on OroPlatform versions and is subject to change.

.. image:: img/release_process/OroReleaseScheduleDark.png


Upgrade Recommendations
-----------------------

Our release cycle offers two primary upgrade models:

- **"Bleeding Edge"** – always upgrade to the newest regular or LTS version to immediately utilize and benefit from new features. Choose this model if you mostly use the application without customizations and are OK with frequent updates.
- **"Stability"** – upgrade from LTS to LTS version to take your time to adopt new features. Choose this model if version upgrade is complicated to you because of the sheer size of your business or due to rich customizations of the system.

.. _Semantic Versioning:    http://semver.org/
