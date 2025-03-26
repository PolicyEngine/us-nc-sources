# us-nc-sources
Source documents for North Carolina

# YAML Metadata Schema

## Required Fields

| Field | Format | Description |
|-------|--------|-------------|
| `file` | String | Standard format: "[Year] [Document Name].pdf" |
| `url` | String | Full URL to the document source |
| `retrieved_on` | Date (YYYY-MM-DD) | Date when the document was retrieved |
| `programs` | List of strings | Main program categories the document belongs to |
| `effective_date` | Date (YYYY-MM-DD) | Date when the document became effective |

## Optional Fields

| Field | Format | Description |
|-------|--------|-------------|
| `subprograms` | List of strings | Specific subcategories within programs |
| `description` | String | Brief description of the document |

## Allowed Values

### Programs
- `income_tax`
- `snap`
- `tanf`
- `use_tax`


### Subprograms
- `Tax Rate`
- `Child Deduction`
- `Child Tax Credit`
- `Itemized Deductions`
- `Standard Deduction`
- `Military Retirement Subtraction`

This list can be expanded as new document types are added to the repository.