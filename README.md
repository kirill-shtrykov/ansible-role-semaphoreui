# ansible-role-semaphoreui
Ansible role for installing and managing Semaphore UI.

# Defaults
```yaml
semaphoreui_version: 2.11.2

# semaphoreui_dialect: postgres               # Required

semaphoreui_bolt_host: /var/lib/semaphore/db.bolt

semaphoreui_mysql_host: localhost
semaphoreui_mysql_user: root
semaphoreui_mysql_pass: changeme
semaphoreui_mysql_name: semaphore
semaphoreui_mysql_options: {}

semaphoreui_postgres_host: localhost
semaphoreui_postgres_user: postgres
semaphoreui_postgres_pass: changeme
semaphoreui_postgres_name: semaphore
semaphoreui_postgres_options: {}

semaphoreui_port: 3000
semaphoreui_interface: ""
semaphoreui_tmp_path: /tmp/semaphore
semaphoreui_web_host: ""
semaphoreui_concurrency_mode: ""
semaphoreui_max_parallel_tasks: 0
# semaphoreui_cookie_hash: changeme           # Required
# semaphoreui_cookie_encryption: changeme     # Required
# semaphoreui_access_key_encryption: changeme # Required

semaphoreui_ldap_binddn: ""
semaphoreui_ldap_bindpassword: ""
semaphoreui_ldap_server: ""
semaphoreui_ldap_searchdn: ""
semaphoreui_ldap_searchfilter: ""
semaphoreui_ldap_mappings_dn: ""
semaphoreui_ldap_mappings_mail: ""
semaphoreui_ldap_mappings_uid: ""
semaphoreui_ldap_mappings_cn: ""

semaphoreui_email_alert: false
semaphoreui_email_sender: ""
semaphoreui_email_host: ""
semaphoreui_email_port: ""

semaphoreui_telegram_alert: false
semaphoreui_telegram_chat: ""
semaphoreui_telegram_token: ""

semaphoreui_slack_alert: false
semaphoreui_slack_url: ""

semaphoreui_microsoft_teams_alert: false
semaphoreui_microsoft_teams_url: ""

semaphoreui_rocketchat_alert: false
semaphoreui_rocketchat_url: ""

semaphoreui_ldap_enable: false
semaphoreui_ldap_needtls: false
```
