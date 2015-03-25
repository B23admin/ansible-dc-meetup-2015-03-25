# Digital Ocean Dev Host

## Configure credentials

``` bash
export DO_CLIENT_ID=<your client id>
export DO_API_KEY=<your api key>
```

## Install Dependencies

``` bash
pip install dopy
```

## Run Playbooks

``` bash
ansible-playbook -vvvv -i hosts digital_ocean.yml
```
