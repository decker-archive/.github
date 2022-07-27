# Derailed :heart: OSS
Welcome to the Derailed GitHub Page!

## Project Index

First off, all of these projects are also indexed on our [progress board](https://github.com/orgs/derailedapp/projects/1) so you can also see them there.

Please note, some of these projects are still work-in-progress and not publicly available.


# Prototypes

- Derailed API - Derailed's Centralized API Implementation.
- Rusk - Rewrite of Derailed's API Implementation for Rust.
- Montero - Derailed's Official Decentralized Implementation.
  **The Speed Demon of Derailed.**

  To give more detail, the idea and main process for Montero is to:
    - be fast, and easily deployable and scalable.
    - be built using GraphQL
    - give you ownership of your own data
    - not have one centralized point of breakage

  It's going to be using different technologies then our Centralized API,
  we'll be moving our Database Service from the insanely fast ScyllaDB to PostgreSQL to give people trying to deploy the service an easier experience.

  **Why GraphQL?**
  
  GraphQL over the years has started to be seen as more reliable, faster and generally scalable then REST,
  it's design also allows us to better power our decentralized nature and help developers aim for impressive goals.

  **Differing from Matrix**

  Montero is supposed to not be like matrix, our goal with our featureset goes as follows:

  - The impressively large amount of features as Discord.
  - The stability of Matrix & Mastodon.
  - As much security as is possible without drasically slowing everything down.
  - As easy to use and deploy as Matrix.
  - Allow massive scalability and maintainability.

  Montero is also supposed to be faster then Matrix[1]

  **More info to come**

  As montero is in A pre-pre-alpha phase, we can't give any ETAs or more features as it would
  allow feature-creep and give us a tight deadline most likely.
  If you want to keep up with news and other announcements, you can join our [Discord Server](https://discord.gg/V7n95jcX2U).

  1. It will be faster then Synapse, not sure about Dendrite, although looking at things like
  routes and other stuff, it seems they still use Synapse in their main production environment.

- Matria - Derailed's Frontend & Application Services.
