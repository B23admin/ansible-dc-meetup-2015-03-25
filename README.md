# Digital Ocean Dev Host

These playbooks were developed and tested on OS X with dependencies
installed via `[homebrew](http://brew.sh/)`.  YMMV on other platforms.

## Configure credentials

``` bash
export DO_CLIENT_ID=<your client id>
export DO_API_KEY=<your api key>
```

## Install Dependencies

``` bash
pip install python ansible dopy apache-libcloud
```

``` bash
brew install knock # or the equivalent for your platform
```

## Run Playbooks

``` bash
ansible-playbook -vvvv -i hosts digital_ocean.yml
```
