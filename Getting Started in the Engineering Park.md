# Getting Started in the Engineering Park
Revision 2

## Introduction
Welcome to the Engineering Park. We are so glad to have you participating in our
community. This guide describes how to get up and running.

## Goal
When you are finished following this guide you will have a scene up and running
on one or more parcels of land within the Engineering Park district in
Decentraland.

## Prerequisites
If you are reading this, then it is assumed that you have already made contact
via hello@engineeringpark.org and have decided to join our community. If you
have come across this document in some other way, then please make contact
before proceeding.

The very first thing to do is present your idea to the leadership team and
request the required amount of land at the desired location within the district.
You will also need to specify whether you are going to be a non-commercial or a
commercial tennant. The requested land may or may not be available and a
negotiation with the leadership team will be necessary to determine what is
actually possible and what is best for the community. With this in mind, make
sure to visit the district and determine where there is unoocupied or available
land which will suit your needs prior to making your request.

In order to get started, you need to decide whether or not you are going to
deploy scenes to your land by yourself or request the leadership team to do it
for you. Note that this decision is not permanent and can always be changed
later.

If you are going to deploy to your land by yourself then you need an Ethereum
wallet to which the land update rights can be allocated. This is the wallet
which will be used to sign the update transaction and therefore it must be
accesible to the person who will execute the deployment.

If you are going to rely on the leadership team to deploy to your land then
please arrange this with them before proceeding. You will also need a source
code repository (e.g. Github) to store the code for your scenes and you will
need to be able to grant read access to this repository to the member of the
leadership team who is assigned to deploy them.

**Note:** The [Builder](https://docs.decentraland.org/builder/builder-101/) is a
simple visual editor tool that lets you create and publish Decentraland scenes
but it can only be used to deploy them when you have land update rights enabling
you to deploy to your land by yourself. If the leadership team is deploying to
your land, then you will need to build your scene using the
[SDK](https://docs.decentraland.org/development-guide/SDK-101/), a powerful tool
that lest you create scenes by writing code.

### Checklist for Prerequisites

- Idea presented to leadership team?
- Non-commercial or commercial?
  - If non-commercial: idea approved by leadership team?
- Land requested and negotiated?
- Deploy scenes yourself or have it done for you?
- If self deploying:
  - Ethereum wallet available?
- If leadership team deploying:
  - Source code repository available?
  - Capability to grant repository read access to leadership team?

## Scene Preparation

The next thing to do is to build a scene. This can be anything from a simple
placeholder containing a sign presenting your business name and logo and a
message saying "coming soon", to a complete scene unique to you and your idea.

As previously mentioned, there are two tools available to build scenes: the
[Builder](https://docs.decentraland.org/builder/builder-101/) and the
[SDK](https://docs.decentraland.org/development-guide/SDK-101/). Note that the
Builder can generate code for use in the SDK, so even if you are relying on the
leadership team to deploy scenes to your land, you can still create the scene in
the Builder and then export the code for deployment via the SDK.

There are a number of possible approaches to bulding scenes:
- create one from scratch,
- clone one of the [example
  scenes](https://github.com/decentraland-scenes/Awesome-Repository) made
  available by the Decentraland Foundation and modify it, or
- ask a member of the community or a 3rd party to create one for you.

## Initial Deployment

Once you have a scene and are ready to deploy it, it is time to contact the
leadership team again to arrange the initial deployment. It is necessary to set
up an online meeting where you can work together the with the member of the
leadership team who is assigned to execute the deployment.

If you are executing the initial deployment yourself then the workflow looks
approximately like this:
1. (you) Have Ethereum wallet ready
1. (leader) Prepare the transaction to allocate land update rights
1. (leader) Execute the allocation transaction
1. (both) Wait until the transaction is succesful...
1. (you) Double check the scene configuration - especially the land coordinates
1. (you) Deploy the scene
1. (both) Explore the new scene

If you are relying on the leadership team to execute the initial deployment then
the workflow looks approximately like this:
1. (you) Grant read access to the scene's source code
1. (leader) Clone the scene's source code, build and preview the scene
1. (leader) Double check the scene configuration - especially the land coordinates
1. (leader) Deploy the scene
1. (both) Explore the new scene

## Subsequent Deployments

If you are executing the deployment then the allocation of land update rights
only needs to be performed once. Once they are allocated you are responsible for
deploying your scenes and you will probably follow a workflow similar to the one
outlined [here](https://docs.decentraland.org/development-guide/dev-workflow/).

If you are relying on the leadership team to execute the deployment then the
workflow is the same each time, although it is assumed that repository access
rights only need to be granted once.

## What Next?

The metaverse is your oyster. Build, create, collaborate, grow. Ask for help or
help others. We can't wait to see what you will do.

## Change Log
Revision 2 on 22 March 2022:
- Removed instructions related to the payment of gas fees using Ethereum. This payment will now be made via a contribution to the [Engineering Park Collective](https://opencollective.com/engineeringpark).