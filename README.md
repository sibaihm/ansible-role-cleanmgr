Disk Cleanup
============

Install the Desktop Experience feature and run Disk Cleanup on Microsoft Windows.

Role Variables
--------------

    cleanmgr_reboot: false
    cleanmgr_sagerun: "0001"

    cleanmgr_active_setup_temp_folders: false
    cleanmgr_branchcache: false
    cleanmgr_downloaded_program_files: false
    cleanmgr_internet_cache_files: false
    cleanmgr_memory_dump_files: false
    cleanmgr_old_chkdsk_files: false
    cleanmgr_previous_installations: false
    cleanmgr_recycle_bin: false
    cleanmgr_service_pack_cleanup: false
    cleanmgr_setup_log_files: false
    cleanmgr_system_error_memory_dump_files: false
    cleanmgr_system_error_minidump_files: false
    cleanmgr_temporary_files: false
    cleanmgr_temporary_setup_files: false
    cleanmgr_thumbnail_cache: false
    cleanmgr_upgrade_discarded_files: false
    cleanmgr_user_file_versions: false
    cleanmgr_windows_defender: false
    cleanmgr_windows_error_reporting_archive_files: false
    cleanmgr_windows_error_reporting_queue_files: false
    cleanmgr_windows_error_reporting_system_archive_files: false
    cleanmgr_windows_error_reporting_system_queue_files: false
    cleanmgr_windows_esd_installation_files: false
    cleanmgr_update_cleanup: true
    cleanmgr_windows_upgrade_log_files: false

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: deekayen.cleanmgr, cleanmgr_reboot: true }

Requirements
------------

None.

Dependencies
------------

None.

License
-------

BSD
