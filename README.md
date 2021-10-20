# Welcome to your introduction to Nuxt.js ✨

This course was set up by [Kaizen Codes](https://www.youtube.com/c/kaizencodes) to help web developers understand the [Nuxt.js](https://nuxtjs.org) Web Development Framework just a little bit better 🚀.

## Prerequisites

This course assumes that you have at least some knowledge about Javascript and web development principles, especially:

- The DOM (Document Object Model)
- Javascript syntax and semantics
- HTML and CSS
- The client-server model
- A little bit about [Vue.js](https://vuejs.org) (Not mandatory)
- Some basic Git knowledge if you're going to use this repo.
- Using NPM or Yarn

## Required software

The only things you need to have installed on your computer are:

- A code editor, I use [vscode](https://code.visualstudio.com/).
- Node.js, which you can download at [Their Website](https://nodejs.org).
- Optionally you can install [Yarn](https://yarnpkg.com), but if you use NPM which comes with Node.js, that's fine too. But I'll be using yarn instead.
- [Git](https://git-scm.com/), If you're going to want to checkout this repo for yourself.

Although this isn't going to hinder what you'll learn if you follow along with this course, it will certainly help cement some of the ideas that are presented. If you get stuck at a certain point reach out via an issue and the community is encouraged to help. 🙌

## Course Structure

Each episode on the [Kaizen Codes](https://www.youtube.com/c/kaizencodes) channel will be linked to a branch on this repo. When following a certain episode, make sure to be checked out on the correct branch if you want to see or use the completed code as reference. Although I highly encourage you to rather try your best to follow along in your own code and only check out the branch when absolutely necessary.

## Planned Course Outline 📕

**IF YOU SEE THIS, THE COURSE IS NOT COMPLETED YET**

The structure of the course is as follows (Links will be added as videos are released.)

| Episode |               Topic                | Link |
| :-----: | :--------------------------------: | :--: |
|   00    |       Creating Nuxt Projects       | N/A  |
|   00    |          The Nuxt Config           | N/A  |
|   01    |         Pages and Routing          | N/A  |
|   01    |           Dynamic Routes           | N/A  |
|   02    |           Data Modeling            | N/A  |
|   02    |   Two way binding and reactivity   | N/A  |
|   03    |         Events & Lifecycle         | N/A  |
|   04    |             Components             | N/A  |
|   05    |        The Nuxt/Vuex Store         | N/A  |
|   06    |             Middleware             | N/A  |
|   07    | Build an API with serverMiddleware | N/A  |
|   08    |              Plugins               | N/A  |
|   09    |     Conclusion, full project.      | N/A  |

### More information on each unit

**00 Creating Nuxt Projects**
Here we'll cover the basics of getting setup in a few different ways. From scratch and using a cli tool.

**00 The Nuxt Config**
A quick rundown on each of the _main_ properties in the nuxt config (at least what is important for now).

- Adding global CSS
- Adding JS scripts
- Adding static assets

**01 Pages and Routing**
In this unit we'll discuss a few of the cool things that Nuxt gives us when it comes to making pages and how the routing works.

- The layouts folder
- Structure of a page
- Properties in the options of a page
- Styling options (installing node-sass)
- Using assets
- Writing template markup
- SEO with Nuxtjs SSR

**01 Dynamic Routes**
In this section we'll look at how we can implement dynamic routes for similar content.

- Naming conventions
- Accessing route properties
- Having fallback content

**02 Data Modeling**
In this unit we'll discuss Data in Nuxt.js and the different ways we can model and control it.

- Static vs. SSR vs. SPA
- Async Data
- Data option
- Usage in templates
- Loading States
- Computed properties
- Watchers
- Conditional Rendering

**02 Two way binding and reactivity**

- Modeling data with inputs
- v-model
- @input and :value
- Disable reactivity
- Reactivity Gotchas

**03 Events and Lifecycle**
In this section we'll take a closer look at a Nuxt apps lifecycle in the different modes.

- Built in application lifecycle events
- Events that fire on elements (:on vs @)
- Writing methods to handle events
- Small intro to nuxt hook events

**04 Components**
This unit will cover the usage of components in Nuxt.

- Benefits and drawbacks
- Writing components
- Props
- Prop Validation
- Functional Components
- Event emitters
- v-model from component
- Slots in components
- Auto import components
- Folder and prefixes
- Styling components (scoping)
- Component transitions

**05 The Nuxt/Vuex Store**
This unit covers the most important bits of the Nuxt/Vuex store.

- Setting up
- Properties: state, getters, mutations, actions
- Modules
- Referencing data in pages and components
- Mapping data in pages and components
- The fetch method, loader and state
- The special NuxtServerInit Action

**06 Middleware**

- Router middleware and context
- Building guards for routes
- serverMiddleware introduction

**07Build an API with serverMiddleware**

- serverMiddleware DEMO
- Small express API

**08 Plugins**

- Custom Plugins
- Inject Property
- Vue Plugins
- SSR Gotchas

**09 Conclusion, full project.**
Just some ending notes and advice for further learning, also the introduction to a real-world full Nuxt.js project built using almost all the items learned in this course:

We're building a CRM in Nuxt.js! 🚀

## Branch Naming Conventions

The `main` branch will contain all the code for every branch grouped together. Although on it's own it may not make a lot of sense as we'll explore different concepts on each branch of this repo and it's not necessarily all going to be related, so the main branch may have strange behaviour if launching a local server.

**Episode Branches**
Each episode will be pre-fixed with a two digit number e.g. `00-getting-started`. Sometimes there will be more than one branch for each episode when we get into different modes or options on a specific topic.

## Getting Started

Feel free to clone this repo and check out the relevant branches as you follow along 🙌

## Contribution

No guidelines here, the code will be pretty much all over the place as each concept will be explained separately. Feel free to open a pull request with any bug fixes / changes.

---

This course by [Kaizen Codes](https://youtube.com/c/kaizencodes) is a free resource. If you'd like to support the channel / creator in anyway, a like and subscribe to the channel will be greatly appreciated. If you're feeling very generous, [Consider Making A Contribution Here](https://kaizen.com.na/payment?ref=kaizencodes). (You can set the desired amount when clicking the button [1USD = Approx. 14N$]). Cheers 🍻
