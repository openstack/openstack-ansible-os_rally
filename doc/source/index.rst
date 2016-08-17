================================
Rally role for OpenStack-Ansible
================================

This Ansible role installs and configures OpenStack Rally.

Default variables
~~~~~~~~~~~~~~~~~

.. literalinclude:: ../../defaults/main.yml
   :language: yaml
   :start-after: under the License.

Required variables
~~~~~~~~~~~~~~~~~~

* ``rally_galera_address``
* ``rally_galera_password``

Example playbook
~~~~~~~~~~~~~~~~

.. literalinclude:: ../../examples/playbook.yml
   :language: yaml
