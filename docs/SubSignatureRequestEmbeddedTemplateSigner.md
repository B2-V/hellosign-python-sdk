# SubSignatureRequestEmbeddedTemplateSigner



## Properties

| Name | Type | Description | Notes |
| ---- | ---- | ----------- | ----- |
| `role`<sup>*_required_</sup> | ```str``` |  Must match an existing role in chosen Template(s). Multiple signers cannot share the same role.  |  |
| `name`<sup>*_required_</sup> | ```str``` |  The name of the signer.  |  |
| `email_address`<sup>*_required_</sup> | ```str``` |  The email address of the signer.  |  |
| `pin` | ```str``` |  The 4- to 12-character access code that will secure this signer&#39;s signature page.  |  |
| `sms_phone_number` | ```str``` |  An E.164 formatted phone number that will receive a code via SMS to access this signer&#39;s signature page.<br><br>**Note**: Not available in test mode and requires a Platinum plan or higher.  |  |


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

