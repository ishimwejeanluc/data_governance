# Multi-Jurisdiction Compliance Response Matrix

**Company:** ShopGhana
**Scenario:** Global customer data deletion requests
**Regulations:** Rwanda Law N° 058/2021, GDPR, CCPA/CPRA

---

## 1. Customer A – Aline (Rwanda)

**Legal Rights Analysis**
Aline has the right to request erasure of her personal data under Article 23 of Rwanda's Law N° 058/2021 of 13/10/2021 relating to the protection of personal data and privacy. The right is not absolute and is subject to exceptions where processing is necessary for compliance with a legal obligation or for the establishment, exercise or defence of legal claims.

**Company Obligations**
- Verify Aline's identity before acting on the request.
- Erase personal data that is no longer necessary for the purposes for which it was collected.
- Inform any third party processing the data, in writing or electronically, of the erasure request (Art. 23).
- Respond to Aline in writing or electronically confirming the action taken.

**Data Retention**
- Can retain: transaction and invoice records required by Rwandan tax and accounting law; AML/KYC records where ShopGhana is a reporting entity.
- Retention period: only until the legal purpose is fulfilled (Art. 52). On expiry, data must be destroyed in a manner that prevents reconstruction.

**Response Deadline**
30 days from receipt of the request (Art. 23).

**Action Steps**
- Verify identity (account-bound email + OTP is proportionate).
- Delete profile, marketing data, and behavioural data from production systems.
- Ring-fence legally required tax/AML records with restricted access.
- Notify third-party recipients of the erasure.
- Log the request and the action taken for audit purposes.

**Draft Response**
> "Dear Aline, your request to delete your personal data under Article 23 of Law N° 058/2021 has been received and will be actioned within 30 days. Your account profile and marketing data have been erased; transaction records required by Rwandan tax law have been retained only for the duration required and will be destroyed thereafter."

---

## 2. Customer B – Lukas (Germany – GDPR)

**Legal Rights Analysis**
Lukas has a strong right to erasure under GDPR Article 17 (the "right to be forgotten"), on the ground that the personal data is no longer necessary for the original purpose and/or that he has withdrawn consent.

**Exemptions**
- Legal compliance — e.g., German tax retention under §147 AO and §257 HGB.
- Establishment, exercise or defence of legal claims (Art. 17(3)(e)).

**Company Obligations**
- Delete personal data without undue delay.
- Notify each recipient of the personal data of the erasure under Art. 19.
- Document the action in the Records of Processing Activities.

**Response Deadline**
One month from receipt under Art. 12(3), extendable by two further months for complex or numerous requests with notice to the data subject within the first month.

**Penalties for Missing Deadline**
Administrative fines up to €20 million or 4% of global annual turnover, whichever is higher.

**Action Steps**
- Verify identity (Art. 12(6)).
- Delete personal data across all production systems.
- Propagate the deletion to third-party processors (CRM, ESP, ad pixels, BI warehouse).
- Retain only the records required by tax law and the open return/warranty window.
- Confirm deletion to Lukas in writing.

**Draft Response**
> "Dear Lukas, we confirm that your personal data has been erased in accordance with GDPR Article 17. Records that German tax law requires us to keep, and a narrow set of records linked to your recent order until the return window closes, have been securely retained as permitted by Article 17(3)."

---

## 3. Customer C – Maria (California – CCPA/CPRA)

**Legal Rights Analysis**
- Right to delete personal information under §1798.105.
- Right to opt out of the sale and sharing of personal information under §1798.120.

**Can Deletion Be Immediate?**
No. Maria has an active return dispute (20 days old). Under §1798.105(d)(1), personal information necessary to complete the transaction and resolve the dispute may be retained until the dispute is closed. The opt-out from sale and sharing, however, must be honoured immediately and is independent of the deletion.

**Company Obligations**
- Confirm receipt of the request within 10 business days.
- Honour the "Do Not Sell or Share My Personal Information" request immediately.
- Pause deletion of dispute-scoped records until the dispute is resolved.
- Delete non-dispute personal information (marketing profile, ad-tech identifiers, telemetry).
- Propagate the opt-out to all service providers, contractors and third parties; respect any Global Privacy Control signal as a valid opt-out.

**Response Deadline**
45 days from receipt, extendable once by 45 days with notice (total 90 days).

**Required Disclosures**
- What categories of personal information were deleted and what were retained.
- The specific §1798.105(d) exemption invoked for any retained data.
- Confirmation that the opt-out from sale and sharing has been implemented.
- That Maria may complain to the California Privacy Protection Agency (CPPA).

**Action Steps**
- Verify identity proportionate to data sensitivity.
- Stop the sale and sharing of personal information immediately across all partners.
- Place deletion on hold for dispute-related records.
- Delete non-dispute personal information within 45 days.
- Complete deletion of the remaining records once the dispute is resolved.

**Draft Response**
> "Dear Maria, we have processed your request to stop the sale and sharing of your personal information; it took effect on receipt. Your deletion request will be completed for all data except records necessary to resolve your active return dispute, which will be deleted once the dispute is closed, as permitted under §1798.105(d)(1)."

---

## 4. Compliance Comparison Table

| Element | Rwanda Law N° 058/2021 | GDPR | CCPA/CPRA |
|---|---|---|---|
| Right to Deletion Exists? | Yes (Art. 23) | Yes (Art. 17 — strong right) | Yes (§1798.105) |
| Exemptions / Conditions | Legal obligation; public interest; legal claims | Legal compliance; defence of legal claims; freedom of expression | Ongoing transactions; dispute resolution; legal obligations |
| Response Deadline | 30 days | 30 days (extendable by 2 months) | 45 days (extendable to 90) |
| Penalties for Non-Compliance | Administrative fine RWF 2M–5M or up to 1% of global turnover; criminal penalties for serious breaches | Up to €20M or 4% global revenue | Fines up to $7,500 per intentional violation |
| Consent Requirements | Freely given, specific, informed and unambiguous (Arts. 3 & 6) | Explicit, informed consent (Art. 7) | Opt-out rights for sale/sharing of personal data |

---

## 5. Key Insights

- GDPR is the strictest with clear timelines and the heaviest penalties.
- CCPA/CPRA focuses strongly on consumer control and opt-out rights.
- Rwanda's Law N° 058/2021 closely mirrors GDPR principles, with a 30-day response window and an explicit obligation to notify third parties of erasure.

---

## Conclusion

ShopGhana must handle each request based on jurisdiction-specific laws, balancing user rights with legal obligations. Proper identity verification, controlled data deletion, and clear communication are essential to maintaining compliance and trust.
