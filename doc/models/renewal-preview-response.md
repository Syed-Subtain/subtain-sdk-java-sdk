
# Renewal Preview Response

## Structure

`RenewalPreviewResponse`

## Fields

| Name | Type | Tags | Description | Getter | Setter |
|  --- | --- | --- | --- | --- | --- |
| `RenewalPreview` | [`RenewalPreview`](../../doc/models/renewal-preview.md) | Required | - | RenewalPreview getRenewalPreview() | setRenewalPreview(RenewalPreview renewalPreview) |

## Example (as JSON)

```json
{
  "renewal_preview": {
    "next_assessment_at": "next_assessment_at2",
    "subtotal_in_cents": 132,
    "total_tax_in_cents": 0,
    "total_discount_in_cents": 250,
    "total_in_cents": 20
  }
}
```

