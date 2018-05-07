# State Machines and Elm: A Match Made in Heaven

## Biography
Bill Peregoy is full-stack software engineer currently employed at The Gnar
Company. After a long career in semiconductor design, Bill moved on to do
software development, largely in Ruby and JavaScript. After being exposed to Elm
for the first time at Strange Loop 2015, Bill has immersed himself into the
functional programming world. Bill is a local advocate for functional
programming both inside his company and at local meetups.


## Abstract
We use state machines all the time in our applications, sometimes without even knowing
it. Most applications have discrete, legal states and a well-defined set of actions
that cause legal state transitions. In many cases, we represent our state
machines in an ad hoc fashion and miss out on the opportunities that a strong
type system provides us. In this talk, We will explore how to use the Elm
architecture and Elm union types to build state machines in our applications.
Through a number of examples, we'll see how the Elm architecture can be
leveraged using the Elm type system to produce reliable, maintainable
applications without invalid states.

## Talk Details
In this talk, I'll show the audience how state machines are at the core of many
common problems in technology. I'll give a brief overview of how state machines are at
the core of much of the hardware that we use and present the difficulties of
representing these state machines in an expressive way. I'll then present
several common situations in application design (HTTP operations, mouse events,
lexical analysis of text). For each of these examples, I'll describe the problem
and demonstrate through code examples how combining the Elm architecture with
state machines built around Elm union types result in more stable, reliable and
maintainable applications.

## Pitch
Elm is a great language from the first day we use it. The architecture, type
system and compiler allow us to create better and more reliable applications
from day one. As we move further along in our Elm knowledge, we begin to realize
that using more union types allows us to create applications with fewer invalid
states and more expressive types. Once we start to identify the state machines
in our applications, we begin to find even more powerful ways to express our
ideas. We end up with code that matches our high-level thinking about the problem at
hand. I worked for many years designing semiconductor chips which were largely
based around hardware implementations of finite state machines. My goal for this
talk is to translate this knowledge into a strategy for building expressive
Elm applications using state machines based on Elm union types.
