# Users

This section is about users in ODM.

!!! type "optional explicit title within double quotes"

    Any number of other indented markdown elements.
    This is the second paragraph.

!!!warning

    "When using AWS Load Balancer Controller v2.5+" The AWS LBC provides a mutating webhook for service resources to set the spec.loadBalancerClass field for service of type LoadBalancer on create. This makes the AWS LBC the default controller for service of type LoadBalancer. You can disable this feature and revert to set Cloud Controller Manager (in-tree controller) as the default by setting the helm chart value enableServiceMutatorWebhook to false with --set enableServiceMutatorWebhook=false . You will no longer be able to provision new Classic Load Balancer (CLB) from your kubernetes service unless you disable this feature. Existing CLB will continue to work fine.
