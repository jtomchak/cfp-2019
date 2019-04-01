# Types Can Help

# Abstract (600 char, what they will learn from your talk and why they care about it)

_undefined_ is not a function. JavaScript is powerful, but it's fast and loose coercion with types can, and probably has come back to bite all of us at least once or twice in production. We can get help in making our code safer, and developing or refactoring with more confidence by adding type annotations about our data. Adding details about whether that function takes strings or ints can save us from unforeseen edge cases. This will take us from starter to super excited about types, and where to direct all that new found energy for type notation.

# Details (more detailed information about how your talk will go down)

Types are there in JavaScript, we just don't see or think in that paradigm regularly, because JavaScript doesn't force us to. They are one of many important tools that can help us make more reasonable code to, not only run but communicate our intent to other developers.

- What are types and type annotation?
  - Beyond primitive types, a short background
  - Types for functions and data objects
  - Example of type notation in other languages and then in TypeScript
- Dip our toes in
  - We have prop-types? let's expand on that idea
  - now we've added type annotated our props, what about the return value from the function?
  - We're adding to a react component piece by piece, type annotation to make our intent more clear to JavaScript, other components, other developers, and future us!
- Looks great, now what?
  - an example of adding types beyond a component, maybe in a reducer or HTTP request, what would that look like?

We'll do the code examples in TypeScript, it has the ability to gently add types as needed no longer forcing us to go all in on a big refactor right away. The goal is to show a couple concrete useful examples of cases for type annotation, and get people excited to try it, and start thinking more about what they want their data to look like, and the how will work itself out.

# Pitch (yourself pitch yourself as the the person capable of making this talk awesome. Why does this talk need to happen? Why are you excited about it? )

Types can be really hard. I went off the deep end and thought learning Haskell was the only way to understand types, but that's not the case. I wish someone had shown me a gentle onboarding to types, and that they aren't stuffy academic fluff, but a really helpful tool to make vastly better decisions and remove a huge amount of mental overhead when it comes to rightly logic in our code.

- I currently hosting and produce a podcast JSToElm for the last couple years, where I spend time every week advocating, documenting, and communicating my struggles with learning types, functional programming paradigms, and a variety of other obstacles in the hope that is helps others.
- I have a chance to speak at our Phoenix React meetup several times a year and get people excited about functional programming, and static types.
- TypeScript is gaining a lot of attention very quickly. I think it's important to help people understand why/what makes using type annotation great, not just that everyone uses it so it must be great.
