OpenStack-Ansible Rally
#######################
:tags: openstack, rally, cloud, ansible
:category: \*nix

This Ansible role installs and configures OpenStack Rally.

Default Variables
=================

.. literalinclude:: ../../defaults/main.yml
   :language: yaml
   :start-after: under the License.

Required Variables
==================

 * rally_galera_address
 * rally_galera_password

Example Playbook
================

.. code-block:: yaml

   - name: Install Rally server
     hosts: rally_all
     user: root
     roles:
       - role: "os_rally"

