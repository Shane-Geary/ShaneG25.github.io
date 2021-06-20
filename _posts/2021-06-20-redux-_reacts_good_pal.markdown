---
layout: post
title:      "Redux- Reacts good pal"
date:       2021-06-20 14:07:39 +0000
permalink:  redux-_reacts_good_pal
---


In this blog post, I'm going to be talking about Redux which is a tool that can be used in React. It is recommended by the developers of Redux that someone new to it first become comfortable in React on it's own. Redux is a pattern for managing application state and if you do not have problems with state management, you might find the benefits of Redux hard to grasp. Though, once your application grows to a point where it's so complex that state becomes hard to follow, Redux swoops in to save the day.

Redux helps to manage state through the "store". State (also called the state tree) is a broad term, but in the Redux API it usually refers to the single state value that is managed by the store and returned by 'getState()'. It represents the entire state of a Redux application, which is often a deeply nested object. By convention, the top-level state is an object or some other key-value collection, but technically it can be any type. Still, it is recommended to do your best to keep the state serializable. Don't put anything inside it that you can't easily turn into JSON. Now, the store itself is an object that holds the application's state tree. There should only be a single store in a Redux app, as the composition happens on the reducer level. The store is where state lives.

We will touch on Redux's "Reducers" here. A reducer (also called a reducing function) is a function that accepts an accumulation and a value and returns a new accumulation. These are used to reduce a collection of values down to a single value. But reducers are not unique to Redux specifically, they are a fundamental concept in functional programming. Reducers calculate a new state given the previous state and an action. So in Redux, the accumulated value is the state object, and the values being accumulated are actions. These must be pure functions which are functions that return that exact same output for the given inputs. They also shouldn't have any side effects. Reducers are the most important concept in Redux. 

From there, we will talk about Redux's "actions". An action is just a plain object that represents an intention to change the state. Any data, whether it be from UI events, network callbacks, or other sources needs to eventually be dispatched as actions. Actions are the only way to get data into the store. Actions must have a type field that indicates the type of action that will be performed. Types can be defined as constants and imported from another module. Since strings are serializable, it is better to use them for "type" over symbols. Other then type, the structuring of an action object is really up to you.

As JavaScript based applications become increasingly complex, our code must manage more state then ever. If a model can update another model, then a view can update a model, which updates another model, and this, in turn, might cause another view to update. That kind of flow is not easy to follow and at some point, you no longer understand what happens in your app as you have lost control over the when, why, and how of its state. So having a tool like Redux is a great solution to this problem!
