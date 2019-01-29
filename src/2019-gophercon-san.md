GopherCon 2019 in San Diego
==

https://www.gophercon.com/

Title
--

Application that deploys myself

Abstract (300 char)
--

In non-containers, Go makes single binary will make deployment easier. But is that way ssh, scp or wget?
The authorization for ssh depends on the worker. Management is complicated.
Dewy will solve this problem by automating the deployment of the application on its own by conforming to sem-ver.

Description
--

The trend is Kubernetes, a container-based immutable infrastructure.
On the other hand, there are cases where a simple VM is used for cost and convenience.
The single binary made by Go makes deployment easy with high portability.
However, there are some things that you need to do at the time of deployment in mutable infrastructure.

- Graceful restart of server
- Generation management for rollback

We shared the Shell Script to do the SCP on the team because the deliverables of Go were portability,
and deployed the application. This creates further problems.

- Shell script updates and copy, copy, copy...
- Management of access authority for SSH

Dewy solves the problem by making the application Semantic Versioning, deploying itself by the application itself.
People do not have to deploy easily even on a single machine.

Note
--

### Outline

1. Self introduction (1minute)
1. Problems and Background (8minutes)
    1. What is deployment in mutable infrastructure (3minutes)
    1. Our mistake in Go application deployment (3minutes)
    1. Why not use capistrano, rsync or ansible (2minutes)
1. Solution (13minutes)
    1. What does dewy do?(6minutes)
    1. Application Development, CI and Semantic Versioning(7minutes)
1. Conclution(3minute)

Meta
--

subject | contet
--- | ---
Talk Format | Keynote 25minutes
Audience Level | Intermediate
Tags | legacy, mutable infrastructure, deployment, go application, CI/CD

Bio
--

Tomohisa is a software developer based in fukuoka, Japan. We organized golang community in fukuoka.
