# Cilium

Cilium has some specific challenges with Rancher Desktop

Status: Work in Progress


* Deploy Rancher Desktop with default settings (I select containerd)
* create override.yaml and copy it to the appropriate directory
* Restart Rancher Desktop (click Troubleshooting | Reset Kubernetes)
* install cilium 
* run cilium status
* get a shell in to the VM and update the shared moount for netns
* smile


## References
https://docs.cilium.io/en/latest/installation/rancher-desktop/
Perplexity provided direction on updating the VM to allow the shared mount

## Todo
* I want to see if I can include the shared-mount configuraiton in the override.yaml file
* figure out how to get Hubble working...
