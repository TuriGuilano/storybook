# Why you will use Storybook for your next project

> So what is Storybook?

"Storybook is a UI development environment for your UI components. With it, you can visualize different states of your UI components and develop them interactively.
Storybook runs outside of your app. So you can develop UI components in isolation without worrying about app specific dependencies and requirements."
source: https://storybook.js.org/basics/introduction/

Let's break up the explanation step by step:

> UI development environment for UI components?

Storybook provides us an isolated environment where all of our components live. This environment is related to our project but stands alone
and does not effect our staging environment which allows us to test and create our components at ease. 

> Visualize different states of your UI components and develop them interactively

Storybook gives us access to a set of awesome addons which make it possible to visualize different states of our components. 
For example; we can see our components change when we pass a different prop; styles || content || state etc.
The perk of immediate feedback during the development process is golden. This way we can debug instant which saves loads of time.

Another awesome addon is the readme addon. This allows us to write a compact component specific readme which we can take in account during the
development process. This way there are no misconceptions about the required functionalities of a component.

You can find more about the process of using addonds that Storybook provides over here: https://storybook.js.org/addons/writing-addons/

> Develop UI components in isolation

We can develop our components in isolation but since we integrated storybook within our project it automatically takes over all the dependencies
that we use and can simulate our application's flow component specific. This way we can test our components without having to worry that our application
will break during the testing. 

> Use case for Storybook?

We all know that React, Vue or Angular can be a bit overwhelming when getting started. Storybook allows you to create a subset and a clear overview
of all your components / component-specific functionalities which makes it easy to understand what the main purpose is of a component.
This way when a new developer joins the team he or she has a clear overview and understanding of the component structure and functionalities. 

I find that Storybook stimulates me to create DRY components and works very well together with the structure of the atomic design principles.
A great article on Atomic design can be found here: https://cheesecakelabs.com/blog/atomic-design-react/
