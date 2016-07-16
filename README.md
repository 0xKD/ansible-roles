# ansible-roles

Run the playbook like this

```bash
ansible-playbook builder.yml -e '{"repo_name":"my-repo","local_repo_path":"/home/ubuntu/repos/my-repo"}'
```

## TODO

- [ ] Add role to setup build machine (ruby, ruby-dev, fpm)
- [ ] Add roles to compile from source and create packages using fpm
