# FAQ

## Why Material-UI?

The short answer is that it's what we've been using in Backstage internally.

The original choice is based on Google's material design being a thorough and well
thought out full design system, with many mature and powerful libraries implementing
both the system itself and auxiliary components that we knew that we would like to use.

It strikes a good balance between power, customisability, and ease of use. Since a core
focus of Backstage is to make plugin developers productive with as few hurdles as
possible, material-ui lets plugin makers both get going easily with well-known tech
and a large flora of components.

## Are you planning on having plugins cooked into the repo or should they be developed in separate repos?

Additional open sourced plugins would be added to the `plugins` directory in this monorepo.

While we encourage using the open soure model, integrators that want to experiment with
Backstage internally may also choose to develop closed source plugins in a manner that suits
them best, for example in their respective Backstage source repository.

## Any plans for integrating with other repository managers such as Gitlab or Bitbucket?

We chose Github by the fact that it is the tool that we are most familiar with and that will naturally
lead to integrations for Github specifically being developed in an early stage.

Hosting this project on Github does not exclude integrations with other alternatives such as Gitlab or
Bitbucket. We believe that in time there will be plugins that will provide functionality for these tools
as well. Hopefully contributed by the community.

And note that implementations of Backstage can be hosted wherever you feel suits your needs best.
