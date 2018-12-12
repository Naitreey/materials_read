Infrastructure Management
=========================

- Ansible v.s. Salt
  https://medium.com/@anthonypjshaw/ansible-v-s-salt-saltstack-v-s-stackstorm-3d8f57149368

Salt
----

- SaltStack Package Repo
  https://repo.saltstack.com/

- Installation
  https://docs.saltstack.com/en/latest/topics/installation/index.html

  * platform-specific installation instructions: Ubuntu
    https://docs.saltstack.com/en/latest/topics/installation/ubuntu.html

- Salt Get Started
  https://docs.saltstack.com/en/getstarted/

  * SaltStack Components
    https://docs.saltstack.com/en/getstarted/overview.html

  * SaltStack Flexibility
    https://docs.saltstack.com/en/getstarted/flexibility.html

  * Saltstack Speed
    https://docs.saltstack.com/en/getstarted/speed.html

  * Salt Fundamentals
    https://docs.saltstack.com/en/getstarted/fundamentals/

  * Salt Configuration Management
    https://docs.saltstack.com/en/getstarted/config/

  * Event-Driven Infrastructure
    https://docs.saltstack.com/en/getstarted/event/

  * Understanding SaltStack
    https://docs.saltstack.com/en/getstarted/system/

    - subsystem diagram
      https://docs.saltstack.com/en/getstarted/system/plugins.html

    - Communication & Security
      https://docs.saltstack.com/en/getstarted/system/communication.html

  * Agentless Salt
    https://docs.saltstack.com/en/getstarted/ssh/

- Salt Documentation
  https://docs.saltstack.com/en/latest/contents.html

  * tutorals

    - Pillar Walkthrough
      https://docs.saltstack.com/en/latest/topics/tutorials/pillar.html

  * Using Salt
    https://docs.saltstack.com/en/latest/topics/using_salt.html

    - Grains
      https://docs.saltstack.com/en/latest/topics/grains/index.html

    - Targeting minions
      https://docs.saltstack.com/en/latest/topics/targeting/index.html

      * Matching the minion id
        https://docs.saltstack.com/en/latest/topics/targeting/globbing.html

      * Targeting using grains
        https://docs.saltstack.com/en/latest/topics/targeting/grains.html

      * Targeting using pillar
        https://docs.saltstack.com/en/latest/topics/targeting/pillar.html

      * Subnet/IP address matching
        https://docs.saltstack.com/en/latest/topics/targeting/ipcidr.html

      * Node groups
        https://docs.saltstack.com/en/latest/topics/targeting/nodegroups.html

      * Batch
        https://docs.saltstack.com/en/latest/topics/targeting/batch.html

      * Compound matchers
        https://docs.saltstack.com/en/latest/topics/targeting/compound.html

    - Storing Static Data In The Pillar
      https://docs.saltstack.com/en/latest/topics/pillar/index.html

    - Remote Execution
      https://docs.saltstack.com/en/latest/topics/execution/index.html

      * Remote execution tutorial
        https://docs.saltstack.com/en/latest/topics/tutorials/modules.html

      * Running Commands on Salt Minions
        https://docs.saltstack.com/en/latest/topics/execution/remote_execution.html

      * salt.modules.schedule
        https://docs.saltstack.com/en/latest/ref/modules/all/salt.modules.schedule.html

  * Runners
    https://docs.saltstack.com/en/latest/ref/runners/

    - Runner Modules

      * jobs
        https://docs.saltstack.com/en/latest/ref/runners/all/salt.runners.jobs.html

  * Job

    - Job Management
      https://docs.saltstack.com/en/latest/topics/jobs/index.html

    - Managing The Job Cache
      https://docs.saltstack.com/en/latest/topics/jobs/job_cache.html

    - Storing job results in an external system
      https://docs.saltstack.com/en/latest/topics/jobs/external_cache.html

  * Configuration Management

    - State System Reference
      https://docs.saltstack.com/en/latest/ref/states/index.html

      * SLS Template Variable Reference
        https://docs.saltstack.com/en/latest/ref/states/vars.html

  * Orchestration
    https://docs.saltstack.com/en/latest/topics/orchestrate/

    - Orchestrate runner
      https://docs.saltstack.com/en/latest/topics/orchestrate/orchestrate_runner.html

  * Configuring Salt
    https://docs.saltstack.com/en/latest/topics/configuration/index.html

    - Configuring Salt
      https://docs.saltstack.com/en/latest/ref/configuration/index.html

  * APIs
    https://docs.saltstack.com/en/latest/topics/api.html

    - Python client API
      https://docs.saltstack.com/en/latest/ref/clients/index.html

    - netapi modules
      https://docs.saltstack.com/en/latest/topics/netapi/index.html

      * rest_cherrypy, a REST API for salt
        https://docs.saltstack.com/en/latest/ref/netapi/all/salt.netapi.rest_cherrypy.html

      * python client library: pepper
        https://github.com/saltstack/pepper

  * access control system
    https://docs.saltstack.com/en/latest/topics/eauth/access_control.html

    - publisher acl system
      https://docs.saltstack.com/en/latest/ref/publisheracl.html

    - external authentication
      https://docs.saltstack.com/en/latest/topics/eauth/index.html

- SaltStack Arch Linux wiki
  https://wiki.archlinux.org/index.php/Saltstack

- CLI.

  * salt(1)

  * salt-key(1)

  * salt-api(1)

  * salt-run(1)

  * salt-cp(1)

  * pepper
