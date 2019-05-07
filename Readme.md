## Simple ssh automation fro developers
This ansible playbook will update the authorized key of the user "dev_admin" in all the mentioned serves in hosts


### USAGE
```
--developer should update file " https://github.com/bharathnoddy/ansible_ssh_access/blob/master/public.keys" with their public keys and update create a pull request.
--Admin will approve the pull request and merge it with the Master
--The merge will trigger a Jenkins jobs  will pull the ansible_ssh_access repo and run this command over it "ansible-playbook playbook.yml"  (assumption server already have ansible_user user)
```
