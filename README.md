Update the repo on the server after building signed packages
============================================================

    ansible-playbook -vvvv -i 'tina,' -e ansible_python_interpreter=/usr/bin/python2 -e force_rebuild_db=1 update_repo.yml 

