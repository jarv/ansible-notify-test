https://github.com/ansible/ansible/issues/4853

`ansible-playbook -c local --limit "localhost," ./test.yml -i "localhost,"`
`ansible-playbook -c local --limit "localhost," ./test.yml -i "localhost," -e "flush=true"`

