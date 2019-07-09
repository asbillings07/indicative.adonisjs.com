---
permalink: different
title: different
category: primitives
gh_url: https://github.com/poppinss/indicative-rules/tree/develop/src/validations/primitives/different.ts
---

Enforces the field value to be different from the targeted field
value.
 
```ts
import { validations } from 'indicative/validator'
 
const rules = {
  secondary_email: 'different:primary_email'
}
 
// or
const rules = {
  secondary_email: [
    validations.different(['primary_email'])
  ]
}
```