SQL injection vulnerability exists in novel-plus v4.1.0
Affected version: v4.1.0

official website: https://novel.xxyopen.com/index.htm

github: https://github.com/201206030/novel-plus

Vulnerability Overview
novel-plus version 4.1.0 has a SQL injection vulnerability. The vulnerability originates from the file "/sys/menu/list?sort=order_num," where manipulating the "sort" parameter can lead to SQL injection. Attackers can exploit this vulnerability to execute unauthorized SQL commands.

Vulnerability details
Vulnerability route: /sys/menu/list

Vulnerable parameter: sort

"Login to the backend using the default account username/password 'admin/admin' to obtain the administrator cookie."
