---
date: 2019-09-24T12:14:34Z
title: "jx edit"
slug: jx_edit
url: /commands/jx_edit/
---
## jx edit

Edit a resource

### Synopsis

Edit a resource

```
jx edit [flags]
```

### Examples

```
  # Lets edit the staging Environment
  jx edit env staging
```

### Options

```
  -h, --help   help for edit
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input (default true)
      --verbose      Enables verbose output
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X
* [jx edit addon](/commands/jx_edit_addon/)	 - Edits the addon configuration
* [jx edit app](/commands/jx_edit_app/)	 - Edits the Jenkins Plugins for a Jenkins App
* [jx edit buildpack](/commands/jx_edit_buildpack/)	 - Edits the build pack configuration for your team
* [jx edit config](/commands/jx_edit_config/)	 - Edits the project configuration
* [jx edit deploy](/commands/jx_edit_deploy/)	 - Edits the deploy kind to use for your project or team
* [jx edit dockerregistryorg](/commands/jx_edit_dockerregistryorg/)	 - Docker registry organisation used for new projects in Jenkins X.
* [jx edit envOrganisation](/commands/jx_edit_envorganisation/)	 - Default git organisation for new environment repositories
* [jx edit environment](/commands/jx_edit_environment/)	 - Edits an Environment which is used to promote your Team's Applications via Continuous Delivery
* [jx edit extensionsrepository](/commands/jx_edit_extensionsrepository/)	 - Sets Extensions Repository in use
* [jx edit gitpublic](/commands/jx_edit_gitpublic/)	 - Are new repositories public by default
* [jx edit gitserver](/commands/jx_edit_gitserver/)	 - Default git server for new repositories
* [jx edit helmbin](/commands/jx_edit_helmbin/)	 - Configures the helm binary version used by your team
* [jx edit organisation](/commands/jx_edit_organisation/)	 - Default git organisation for new repositories
* [jx edit pipelineuseremail](/commands/jx_edit_pipelineuseremail/)	 - Users email used by pipeline. Is given write permission on new repositories.
* [jx edit pipelineusername](/commands/jx_edit_pipelineusername/)	 - User used by pipeline. Is given write permission on new repositories.
* [jx edit storage](/commands/jx_edit_storage/)	 - Configures the storage location for stashing files or storing build logs for your team
* [jx edit userroles](/commands/jx_edit_userroles/)	 - Edits the roles associated with a User

###### Auto generated by spf13/cobra on 24-Sep-2019