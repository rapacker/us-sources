# us-sources
Source documents for federal US policies.

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
- `poverty_guidelines`


### Subprograms
- `tax_rate`
- `child_deduction`
- `child_tax_credit`
- `itemized_deductions`
- `standard_deduction`
- `military_retirement_subtraction`

This list can be expanded as new document types are added to the repository.