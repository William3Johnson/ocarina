# ocarina

ansible scripts to deploy greymass projects

* [light api](https://github.com/cc32d9/eosio_light_api.git)

    ```
    # edit variables in inventory/lightapi and inventory/host_vars/lightapi_server_01/vars.yml
    ansible-playbook -i inventory/lightapi lightapi.yml
    ```
