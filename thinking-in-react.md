# Thinking in React

[Thinking in React](https://reactjs.org/docs/thinking-in-react.html) is Facebook's opinion on how "to build big, fast Web apps with JavaScript."

The knowledge distilled here comes from building their own Facebook and Instagram products. 

At the top of the document they rush to state React has a special way to think about app development. It's a different thought process than the previous attempts.

## Start with a  Mock

In [What Are the React Team Principles?](https://overreacted.io/what-are-the-react-team-principles/) Dan Abramov, React core-member and developer advocate starts with: UI before API.

Now that's a new approach. Before React the thought process was:

1. The UI/UX design team creates mockups and wireframes.
2. The back-end team creates the API.
3. The front-end team merges the two together. 

Facebook realised the drawbacks of this approach. What the users see -- the app -- is the result of a complicated merging process across departments, done at the end.

Instead, they said, let's start with front-end then connect everything else to it.  UI before API.

In Thinking in React front-end developers are in power. They mock up the application.

### Single Responsibility Principle (SRP)

New principles build new paradigms. 

A decade ago Ruby on Rails made MVC, REST and CRUD mainstream together with the **Don't Repeat Yourself (DRY)** principle.

Now Facebook introduces another principle, SRP, to the web. The concept is not new, is part of the UNIX philosophy: do one thing and do it well.

Thinking in React says breaking up the UI into components should follow this principle of simplicity. 

"A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents. 

Once mastered this principle drives all decisions during a React project. From front-end down the whole stack and process.

## First, build a static version

The mocking process assures all stakeholders about the common understanding of the business requirements. And offers the first proof of concept the app will follow the specifications.

Next, Thinking in React says, let's wire in data. Let's repeat the success of the previous UI mocking process now on a level up.

Static data means no back-end work involved yet. Front-end tools are capable to generate text, images, and content necessary to give a glimpse how the final app will look.

The end of this phase marks a milestone. The app works infantly yet visibly leaving no doubts about. 

