# BBBLoadBalancer-cookbook

You can use this cookbook to setup a BigBlueButton load balancer with Chef

## Chef cookbook

### Dependencies

- [Chef DK](https://downloads.chef.io/chef-dk/)

### BBBLoadBalancer::default

Include `BBBLoadBalancer` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[BBBLoadBalancer::default]"
  ]
}
```

## Vagrant

### dependencies

    [Chef DK](https://downloads.chef.io/chef-dk/)

### vagrant required modules

    $ vagrant plugin install vagrant-berkshelf
    $ vagrant plugin install vagrant-omnibus

## Start Vagrant box

    $ berks install
    $ vagrant up
