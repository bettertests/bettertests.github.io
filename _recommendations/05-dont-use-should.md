---
layout: recommendation
title:  "Don't use 'should'"
---
"Should" is repetitive and doesn't provide useful or meaningful information
about expected behavior. Use actionable, present tense language in descriptions.

### Bad
{: .spec-wrong}

```javascript
it('should sign up a user', () => {});

it('should prompt a guest to sign up', () => {});

it('should add to cart', () => {})
```

### Good
{: .spec-right}

```javascript
it('signs up a user', () => {});

it('prompts a guest to sign up', () => {});

it('adds to cart', () => {})
```
