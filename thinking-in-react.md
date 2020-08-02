# Thinking in React

Thinking in React[^1] is Facebook's opinion on how "to build big, fast Web apps with JavaScript."

The knowledge distilled here comes from building their own Facebook and Instagram products. 

The document presents a different thought process about app development:

1. Introduces a new principle
2. Shifts control to the front-end
3. Proposes steps to gradually build the product and assure stakeholders

## The Single Responsibility Principle (SRP)

A decade ago Ruby on Rails came up with the MVC, REST, CRUD architecture built on the **Don't Repeat Yourself (DRY)** principle.

Now Facebook introduces another principle, SRP, to the web. The concept is not new, is part of the UNIX philosophy: do one thing and do it well.

Thinking in React says applications should be broken into simple components. 

"A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents. 

## UI before API

UI before API[^2] is a new approach on collaboration. Before React:

1. The UI/UX design team created mockups and wireframes.
2. The back-end team created the API.
3. The front-end team combined them together. 

Facebook realised the drawbacks of this approach. The final result -- what the users see, the app -- gets assembled at the end.

Instead, they said, let's reverse the process. Start all up-front then connect everything else to it. UI before API.

This approach results better and more often, more real feedback; empowers front-end and gives other departments a supportive role.

## Start with a Mock

Start the application design and development by mocking up the UI in the browser using components following SRP.

The result will assure stakeholders about the understanding of the business requirements. 

And offers a proof of concept the app is feasible and follows the specifications.

## Build a static version first

Next, Thinking in React says, let's wire in data. Let's repeat the success of the previous UI mocking process on a level up.

Static data mocking means no back-end work involved yet. Front-end tools are capable to generate text, images, and content.

All necessary to give a glimpse how the final app will look.

## Add interactivity

After a static prototype comes the dynamic prototype with user interactions and data loading.

After this step different teams can enter the project and are kept in sync by front-end. 

The data needs of the front-end are defined and back-end is ready to start the implementation. 

The UI/UX design team is ready to take the live, responsive prototype and apply the branding.

## Footnotes
[^1]: [Thinking in React](https://reactjs.org/docs/thinking-in-react.html) 
[^2]: [What Are the React Team Principles?](https://overreacted.io/what-are-the-react-team-principles/)


