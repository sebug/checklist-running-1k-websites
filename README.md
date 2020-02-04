# Notes for: Your checklist for running thousands of websites
Robert Douglass

Nestlé giving up on Kubernetes, going with platform.sh

## Development Process
1 to 4 stars - 1 star is no source control :-)

4 star: you get your own development server, automated access control

## Developer environments
Automated system reproduces the cloud environment: https://lando.dev

## Stakeholder engagement
Send a URL that contains a specific feature on a specific site.

## Coding standards
Pin your versions of third party libraries!

## Code quality
Linting and unit tests can block a deploy.

## Code deployment
4 star: Immutable deployments

## Interruption
Robert mentions a talk about doing it uninterrupted for databases - which one?

## Deployment
Pull-based model.

## Infrastructure
If you have to open a ticket for anything - 1 star.

Parity of infrastructure versions on dev and prod.

## Isolation
Platform.sh - multitenant docker images for some clients, dedicated hardware for the rest.

## Disaster recovery
4 stars: automatic replacement of failed infrastructure, data attaches itself to the new services that come up.

## Immutable
4 stars - your code on a read-only file system.

## Updates & maintenance
Security checks: http://techbeacon.com/app-dev-testing/13-tools-checking-security-risk-open-source-dependencies

## What leads to an update
Most of the time, only the references to upstream packages change.

## Backups
Disk-level snapshots

https://docs.ceph.com/docs/giant/rbd/rbd-snapshot


