# EPEL

An Ansible role that installs EPEL repository on RHEL 5/6/7 and its derivatives.


## Role Variables

Available variables and their default values are listed below:

* `epel_enabled: yes` - enable or disable EPEL stable repository.
* `epel_testing_enabled: no` - enable or disable EPEL testing repository.


## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    ---
    - hosts: all
      roles:
        - ezamriy.epel
```


## License

MIT


## Authors

* [Eugene Zamriy](https://github.com/ezamriy)
* [Vasily Kleschov](https://github.com/korulag)
