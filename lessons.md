# Tuple
1. Tuple[number] gets all the value of this Tuple in union. [see](./playground/00011-easy-tuple-to-object.ts)
2. One can use infer to get types of elements in Tuple. [see](./playground/00014-easy-first-of-array.ts)
3. Tuple["length"] gets the length of readonly tuple. [see](./playground/00018-undefined-length-of-tuple.ts)
4. Use ... to spread a Tuple

# Union
1. [Distributive Conditional Types](https://godlanbo.com/blogs/43)

# Build-in type tools
1. PromiseLike

# Operators
1. extends: "A extends B" is used to determine whether A can be assigned to B, and it can be simplified as A is a subclass and B is a superclass. It is used to check whether a subclass can be assigned to a superclass.

# Something Really Deep
1. [When inferring from a type with multiple call signatures (such as the type of an overloaded function), inferences are made from the last signature (which, presumably, is the most permissive catch-all case). It is not possible to perform overload resolution based on a list of argument types.](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-2-8.html#type-inference-in-conditional-types)
2. [co-variant positions and contra-variant positions 1](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-2-8.html#type-inference-in-conditional-types)
   1. [variance explanation](https://stackoverflow.com/a/61703116/11159664)
3. [how this "Equal" works](https://github.com/Microsoft/TypeScript/issues/27024#issuecomment-510924206)

# References
1. https://juejin.cn/post/6999280101556748295#heading-11
2. 