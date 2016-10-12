.NET Framework 4.5.2
====================

Install (or uninstall) Microsoft .NET Framework 4.5.2 on Windows.

Requirements
------------

The target Windows machines must have whitelisted Internet access to download the .NET installer from download.microsoft.com.

Role Variables
--------------

By default, this role installs the .NET Framework. Toggling the dotnet452_uninstall variable from false to true will uninstall the framework if it exists.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: deekayen.dotnet452, dotnet452_uninstall: false }

License
-------

BSD
