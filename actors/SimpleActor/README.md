# SimpleActor

A very basic first *getting-started* lab

One Actor is implemented but replicated in many instances.

## Lab description

* Deploy a controller that can deploy actors
* Synchronize the actors with controller
* Explore state consistency. I.e. verifying that each proxy addresses it's
  actor and no-one else's - even under heavy load.
* Punish `Service Fabric` by running as many actors as possible
* Re-use proxies

## Exercise

Is proxies can safely be reused, what happens if more than one controller
uses the same actor?

