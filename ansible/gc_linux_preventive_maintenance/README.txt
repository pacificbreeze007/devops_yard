.
├── ansible.cfg
├── git_update.sh
├── hosts
├── logs
│   └── ansible.log
├── patch.yml
├── README.txt
├── retry
│   └── patch.retry
└── roles
    ├── backup
    │   ├── tasks
    │   │   ├── create_snapshot.yml
    │   │   └── main.yml
    │   └── vars
    │       └── credentials.yml
    ├── cleanup
    │   └── tasks
    │       ├── main.yml
    │       ├── remove_old_kernel_devel.yml
    │       ├── remove_old_kernel_tools.yml
    │       └── remove_old_kernel.yml
    ├── linux_patching
    │   └── meta
    │       └── main.yml
    ├── patchOS
    │   └── tasks
    │       ├── apply_package_updates.yml
    │       ├── main.yml
    │       └── reboot_server.yml
    ├── remanage_node
    │   ├── library
    │   │   └── orion_node_manage.py
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   └── vars
    │       └── credentials.yml
    ├── unmanage_node
    │   ├── library
    │   │   └── orion_node_manage.py
    │   ├── README.md
    │   ├── tasks
    │   │   └── main.yml
    │   └── vars
    │       └── credentials.yml
    └── vmtools
        ├── defaults
        │   └── main.yml
        ├── files
        │   └── VMwareTools-10.2.1-8267844.tar.gz
        └── tasks
            └── main.yml

24 directories, 29 files
