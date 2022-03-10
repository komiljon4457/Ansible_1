### Ansible Work Space

#### Running ping command to two other server 
`ansible {hostname} -m ping`
#### Running ansible playbook 
`ansible-playbook {filename.yaml}`

#### Running specific shell command on specific hosts
`ansible {hostname} -m shell -a "command here"
