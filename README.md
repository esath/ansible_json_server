
This is demo-database with some employee data.

See json-server page for more information:
 https://github.com/typicode/json-server


Install json-server:
 $ npm install -g json-server


Run it:
 $ json-server --watch data1.json


Update json-file with Ansible:
 $ ansible-playbook ansi_json.yml -e "x_id=101 x_name=Sirpa x_last_name=Korhonen x_email=sirpa.korhonen@test.net"


Check json-data:
 http://localhost:3000/employees

