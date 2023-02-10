## 05 Feb 23 00:14 UTC

Success: false

### Versions



### Error

[31m[0mThere are some problems with the configuration, described below.

The Terraform configuration must be valid before initialization so that
Terraform can determine which modules and providers need to be installed.[0m[0m
[33m[33m╷[0m[0m
[33m│[0m [0m[1m[33mWarning: [0m[0m[1mVersion constraints inside provider configuration blocks are deprecated[0m
[33m│[0m [0m
[33m│[0m [0m[0m  on main.tf line 2, in provider "azurerm":
[33m│[0m [0m   2:   version = [4m"=1.36.0"[0m[0m
[33m│[0m [0m
[33m│[0m [0mTerraform 0.13 and earlier allowed provider version constraints inside the
[33m│[0m [0mprovider configuration block, but that is now deprecated and will be
[33m│[0m [0mremoved in a future version of Terraform. To silence this warning, move the
[33m│[0m [0mprovider version constraint into the required_providers block.
[33m╵[0m[0m
[0m[0m
[31m[31m╷[0m[0m
[31m│[0m [0m[1m[31mError: [0m[0m[1mInvalid quoted type constraints[0m
[31m│[0m [0m
[31m│[0m [0m[0m  on variables.tf line 2, in variable "name":
[31m│[0m [0m   2:   type        = [4m"string"[0m[0m
[31m│[0m [0m
[31m│[0m [0mTerraform 0.11 and earlier required type constraints to be given in quotes,
[31m│[0m [0mbut that form is now deprecated and will be removed in a future version of
[31m│[0m [0mTerraform. Remove the quotes around "string".
[31m╵[0m[0m
[0m[0m
[31m[31m╷[0m[0m
[31m│[0m [0m[1m[31mError: [0m[0m[1mInvalid quoted type constraints[0m
[31m│[0m [0m
[31m│[0m [0m[0m  on variables.tf line 8, in variable "environment":
[31m│[0m [0m   8:   type        = [4m"string"[0m[0m
[31m│[0m [0m
[31m│[0m [0mTerraform 0.11 and earlier required type constraints to be given in quotes,
[31m│[0m [0mbut that form is now deprecated and will be removed in a future version of
[31m│[0m [0mTerraform. Remove the quotes around "string".
[31m╵[0m[0m
[0m[0m
[31m[31m╷[0m[0m
[31m│[0m [0m[1m[31mError: [0m[0m[1mInvalid quoted type constraints[0m
[31m│[0m [0m
[31m│[0m [0m[0m  on variables.tf line 14, in variable "location":
[31m│[0m [0m  14:   type        = [4m"string"[0m[0m
[31m│[0m [0m
[31m│[0m [0mTerraform 0.11 and earlier required type constraints to be given in quotes,
[31m│[0m [0mbut that form is now deprecated and will be removed in a future version of
[31m│[0m [0mTerraform. Remove the quotes around "string".
[31m╵[0m[0m
[0m[0m
[31m[31m╷[0m[0m
[31m│[0m [0m[1m[31mError: [0m[0m[1mInvalid quoted type constraints[0m
[31m│[0m [0m
[31m│[0m [0m[0m  on variables.tf line 20, in variable "dns_prefix":
[31m│[0m [0m  20:   type        = [4m"string"[0m[0m
[31m│[0m [0m
[31m│[0m [0mTerraform 0.11 and earlier required type constraints to be given in quotes,
[31m│[0m [0mbut that form is now deprecated and will be removed in a future version of
[31m│[0m [0mTerraform. Remove the quotes around "string".
[31m╵[0m[0m
[0m[0m
[31m[31m╷[0m[0m
[31m│[0m [0m[1m[31mError: [0m[0m[1mInvalid quoted type constraints[0m
[31m│[0m [0m
[31m│[0m [0m[0m  on variables.tf line 26, in variable "plan_tier":
[31m│[0m [0m  26:   type        = [4m"string"[0m[0m
[31m│[0m [0m
[31m│[0m [0mTerraform 0.11 and earlier required type constraints to be given in quotes,
[31m│[0m [0mbut that form is now deprecated and will be removed in a future version of
[31m│[0m [0mTerraform. Remove the quotes around "string".
[31m╵[0m[0m
[0m[0m
[31m[31m╷[0m[0m
[31m│[0m [0m[1m[31mError: [0m[0m[1mInvalid quoted type constraints[0m
[31m│[0m [0m
[31m│[0m [0m[0m  on variables.tf line 32, in variable "plan_sku":
[31m│[0m [0m  32:   type        = [4m"string"[0m[0m
[31m│[0m [0m
[31m│[0m [0mTerraform 0.11 and earlier required type constraints to be given in quotes,
[31m│[0m [0mbut that form is now deprecated and will be removed in a future version of
[31m│[0m [0mTerraform. Remove the quotes around "string".
[31m╵[0m[0m
[0m[0m

---
