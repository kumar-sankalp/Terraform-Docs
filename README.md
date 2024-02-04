# Terraform-Docs

.
├── README.md
├── azure-pipelines.yml
├── pipelines
│   ├── scripts
│   │   ├── initialize.sh
│   │   ├── terragrunt_exec.sh
│   │   └── terragrunt_init.sh
│   └── templates
│       └── terragrunt-command.yml
├── terraform
│   └── modules
│       ├── VNET
│       │   ├── README.md
│       │   ├── main.tf
│       │   ├── outputs.tf
│       │   └── variables.tf
│       ├── VM
│       │   ├── README.md
│       │   ├── main.tf
│       │   ├── outputs.tf
│       │   ├── variables.tf
│       └── SA
│           ├── README.md
│           ├── main.tf
│           ├── outputs.tf
│           └── variables.tf
└── terragrunt
    ├── config.yml
    ├── dev
    │   ├── VNET
    │   │   └── terragrunt.hcl
    │   ├── VM
    │   │   └── terragrunt.hcl
    │   └── SA
    │       └── terragrunt.hcl
    ├── production
    │   ├── VNET
    │   │   └── terragrunt.hcl
    │   ├── VM
    │   │   └── terragrunt.hcl
    │   └── SA
    │       └── terragrunt.hcl
    ├── terragrunt.hcl
    └── test
        ├── VNET
        │   └── terragrunt.hcl
        ├── VM
        │   └── terragrunt.hcl
        └── SA
            └── terragrunt.hcl
