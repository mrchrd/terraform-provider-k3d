---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "k3d_registry Resource - terraform-provider-k3d"
subcategory: ""
description: |-
  k3d-managed registry.
---

# k3d_registry (Resource)

k3d-managed registry.



<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **name** (String) Node name.

### Optional

- **id** (String) The ID of this resource.
- **image** (String) Node name.
- **port** (Block List, Max: 1) Select which port the registry should be listening on on your machine (localhost). (see [below for nested schema](#nestedblock--port))

<a id="nestedblock--port"></a>
### Nested Schema for `port`

Optional:

- **host** (String)
- **host_ip** (String)
- **host_port** (Number)


