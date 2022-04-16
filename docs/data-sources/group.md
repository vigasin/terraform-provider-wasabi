---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "wasabi_group Data Source - terraform-provider-wasabi"
subcategory: ""
description: |-
  
---

# wasabi_group (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `group_name` (String)

### Optional

- `id` (String) The ID of this resource.

### Read-Only

- `arn` (String)
- `group_id` (String)
- `path` (String)
- `users` (List of Object) (see [below for nested schema](#nestedatt--users))

<a id="nestedatt--users"></a>
### Nested Schema for `users`

Read-Only:

- `arn` (String)
- `path` (String)
- `user_id` (String)
- `user_name` (String)

