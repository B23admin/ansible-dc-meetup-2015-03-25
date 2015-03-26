These playbooks were developed and tested on OS X with dependencies
installed via [`homebrew`](http://brew.sh/).  YMMV on other platforms.

# Digital Ocean Dev Host

## Configure credentials

``` bash
export DO_CLIENT_ID=<your client id>
export DO_API_KEY=<your api key>
```

## Install Dependencies

``` bash
brew install python knock # or the equivalent for your platform
```

``` bash
pip install ansible dopy
```

## Run Playbook

``` bash
ansible-playbook -i hosts digital_ocean.yml
```

# Mesosphere on Google Cloud

## Configure credentials

Follow the instructions
[here](http://docs.ansible.com/guide_gce.html#credentials) to set up
Google Compute credentials.

## Install Dependencies

``` bash
pip install apache-libcloud
```

## Run Playbook

``` bash
ansible-playbook -i hosts google_compute.yml
```
