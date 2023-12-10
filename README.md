# Typescript Labs

## Lab 16: Selectively Construct Types from Other Types

file: `/src/16-omit-and-pick.problem.ts`

We've looked at inheriting and combining types.

But what if we want to be more selective?

Challenge
Given this User interface, create a new object type that only includes the firstName and lastName properties:

```ts
interface User {
  id: string;
  firstName: string;
  lastName: string;
}
```

Read through the TypeScript Utility Type docs to see what you can find.